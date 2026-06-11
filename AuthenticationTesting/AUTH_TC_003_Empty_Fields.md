## **AUTH_TC_003:** Empty Fields

> **Summary:** This test case verifies the successful login of a user with empty fields. <br>

**Preconditions:** _None_

Scenario 1

| # | Steps | Expected Behavior |
| ----- | ----- | ----- |
| 1 | Open login page | The login page is displayed successfully |
| 2 | Leave email field empty | The email field is empty |
| 3 | Leave password field empty | The password field is empty |
| 4 | Click the login button | The user is not redirected to the dashboard |

Scenario 2

| # | Steps | Expected Behavior |
| ----- | ----- | ----- |
| 1 | Open login page | The login page is displayed successfully |
| 2 | Enter valid email | The email address is accepted |
| 3 | Leave password field empty | The password field is empty |
| 4 | Click the login button | The user is not redirected to the dashboard |

Scenario 3

| # | Steps | Expected Behavior |
| ----- | ----- | ----- |
| 1 | Open login page | The login page is displayed successfully |
| 2 | Leave email field empty | The email field is empty |
| 3 | Enter valid password | The password is accepted |
| 4 | Click the login button | The user is not redirected to the dashboard |