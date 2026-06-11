## **EMAIL_TC_001:** Send Result Email

> **Summary:** This test case verifies the ability of the app to send results to email.

**Preconditions:** _Valid email configured_

Scenario 1

| # | Steps | Expected Behavior |
|-----|-----|-----|
| 1 | Complete exam processing. | System generates an Exam Result record. |
| 2 | Trigger email sending | System queues email to background job. |
| 3 | Check email | Email received with correct summary and attachments. |
