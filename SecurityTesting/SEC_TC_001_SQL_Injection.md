## **SEC_TC_001:** SQL Injection

> **Summary:** This test case verifies the ability of the app to prevent SQL injection attacks.

**Preconditions:** _Login Page exists_

Scenario 1

| # | Steps | Expected Behavior |
|-----|-----|-----|
| 1 | Enter ' OR 1=1 -- in username field. | System should reject the input and display an error message. |
| 2 | Enter a space, backspace, then space again in username field. | System should reject the input and display an error message. |