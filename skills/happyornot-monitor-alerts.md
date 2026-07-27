---
name: Monitor HappyOrNot alerts
description: Read alert specifications, poll triggered alerts, and read their comment threads.
api: openapi/happyornot-openapi-original.yml
operations: [listAlertSpecifications, listAlerts, listAlertComments]
---

# Monitor alerts

HappyOrNot triggers alerts when feedback crosses configured thresholds. The API is poll-based (no push/webhook), so poll on an interval.

## Auth
`X-HON-API-Token` header. Alerts are scoped to accessible experience points.

## Steps
1. `listAlertSpecifications` (`GET /alert-specifications.json`) — the rules that generate alerts, keyed by `alertSpecificationId`, `surveyId`, `experiencePointId`.
2. `listAlerts` (`GET /alerts.json`) — triggered alerts. Filter by `period`/date and `experiencePointId`; each alert carries `alertSpecificationId`, `surveyId`, `experiencePointId`, and `acknowledgedByUserId` when acknowledged.
3. `listAlertComments` (`GET /alert-comments.json`) — the comment thread for handling, linked via `alertId` and `userId`.

## Conventions
- Poll `listAlerts` with `order=desc` and a recent `period` (e.g. `today`); page with `offset`/`limit` while `X-More-Available` is `true`.
- Join comments and users with `listUsers` (`GET /users.json`) if you need author names.
- No idempotency/write surface — this API only reads.
