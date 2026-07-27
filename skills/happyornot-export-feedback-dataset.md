---
name: Export a full HappyOrNot feedback dataset
description: Pull every feedback type (button, follow-up, text, demographics, contact details, metadata) for a period into JSON or CSV.
api: openapi/happyornot-openapi-original.yml
operations: [listButtonFeedbacks, listFollowupFeedbacks, listTextFeedbacks, listDemographics, listContactDetails, listMetadata]
---

# Export a feedback dataset

Assemble a complete customer-experience dataset for BI/analytics from the HappyOrNot Customer API v2.

## Auth
`X-HON-API-Token` header on every call. Token access scopes what you can export.

## Steps
Call each results endpoint for the same time window (`period` or `startDate`/`endDate`), joining on `feedbackId`, `smileyId`, `surveyId`, `experiencePointId`:
1. `listButtonFeedbacks` (`GET /results/button-feedbacks.{format}`) — the always-present smiley/NPS rating.
2. `listFollowupFeedbacks` (`GET /results/follow-up-feedbacks.{format}`) — selected follow-up options.
3. `listTextFeedbacks` (`GET /results/text-feedbacks.{format}`) — freeform text.
4. `listDemographics` (`GET /results/demographics.{format}`) — AI age/gender estimate (Smiley Touch only).
5. `listContactDetails` (`GET /results/contact-details.{format}`) — contact-request name/email/phone.
6. `listMetadata` (`GET /results/metadata.{format}`) — arbitrary key-value pairs per feedback.

## Conventions
- Choose `.json` for joining programmatically or `.csv` for spreadsheet/BI import (`separator` param controls the CSV delimiter).
- Page every endpoint with `offset`/`limit`; loop while `X-More-Available` is `true`.
- Keep the same `period`/date range across all six calls so the rows reconcile.
