## **SEC_TC_002:** XSS Attack

> **Summary:** This test case verifies the ability of the app to prevent XSS attacks.

**Preconditions:** _Input field is available_

Scenario 1

| # | Steps | Expected Behavior |
|-----|-----|-----|
| 1 | Enter <script>alert('XSS')</script> in username field. | System should reject the input and display an error message. |