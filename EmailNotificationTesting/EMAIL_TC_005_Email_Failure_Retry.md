## **EMAIL_TC_005:** Email Failure Retry

> **Summary:** This test case verifies the ability of the app to retry sending emails when the system is down.

**Preconditions:** _Network disabled_

Scenario 1

| # | Steps | Expected Behavior |
|-----|-----|-----|
| 1 | Disable network | System should display network error message. |
| 2 | Trigger email sending | Email queue fails silently or stores for retry. |
| 3 | Enable network | Email retry job sends queued email. |