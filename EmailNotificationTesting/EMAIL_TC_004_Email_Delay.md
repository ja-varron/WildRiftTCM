## **EMAIL_TC_004:** Email Delay

> **Summary:** This test case verifies the response time of the app to send results to email.

**Preconditions:** _Email system active_

Scenario 1

| # | Steps | Expected Behavior |
|-----|-----|-----|
| 1 | Complete exam processing. | System generates an Exam Result record. |
| 2 | Trigger email sending | System queues email to background job. |
| 3 | Check email | Email received within acceptable delay. |