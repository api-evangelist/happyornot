---
name: Fetch HappyOrNot button feedback for a location
description: Resolve an experience point and its surveys, then pull the smiley/NPS button feedback for a time window.
api: openapi/happyornot-openapi-original.yml
operations: [listExperiencePoints, listSurveys, listButtonFeedbacks]
---

# Fetch button feedback

Use the HappyOrNot Customer API v2 (`https://api.happy-or-not.com/v2/`, read-only).

## Auth
Send the API token on every request as the `X-HON-API-Token` header (or `?auth=<token>`). Tokens are package-scoped to the experience points the issuer can access — a 403 means the token lacks access to the requested `experiencePointId`/`surveyId`.

## Steps
1. `listExperiencePoints` (`GET /experience-points.json`) — find the target `experiencePointId`. Experience points and groups form a hierarchical tree.
2. `listSurveys` (`GET /surveys.json`) — find the `surveyId`(s) associated with that experience point.
3. `listButtonFeedbacks` (`GET /results/button-feedbacks.json`) — filter with `experiencePointId` and/or `surveyId`, plus a time window via `period` (e.g. `last-month`) or `startDate`/`endDate`.

## Conventions
- Paginate with `offset`/`limit` (limit default 1000, max 10000). Keep requesting while the `X-More-Available` response header is `true`.
- Set `order=desc` for newest-first.
- Use `includeMisuse`/`includeSpam` deliberately; they default to excluding flagged feedback.
- Errors are plain HTTP status: 400 bad params, 401 bad/missing token, 403 not authorised.
