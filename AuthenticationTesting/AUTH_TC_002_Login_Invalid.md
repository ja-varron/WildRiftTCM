## **AUTH_TC_002:** Login Invalid 

> **Summary:** This test case verifies the successful login of a user with invalid credentials. <br>

**Preconditions:** _User account exists_

Scenario 1

| # | Steps | Expected Behavior |
| ----- | ----- | ----- |
| 1 | Open login page | The login page is displayed successfully |
| 2 | Enter invalid email | The email address is not accepted |
| 3 | Enter invalid password | The password is not accepted |
| 4 | Click the login button | The user is not redirected to the dashboard |

Scenario 2

| # | Steps | Expected Behavior |
| ----- | ----- | ----- |
| 1 | Open login page | The login page is displayed successfully |
| 2 | Enter valid email | The email address is accepted |
| 3 | Enter invalid password | The password is not accepted |
| 4 | Click the login button | The user is not redirected to the dashboard |

Scenario 3

| # | Steps | Expected Behavior |
| ----- | ----- | ----- |
| 1 | Open login page | The login page is displayed successfully |
| 2 | Enter invalid email | The email address is not accepted |
| 3 | Enter valid password | The password is accepted |
| 4 | Click the login button | The user is not redirected to the dashboard |


