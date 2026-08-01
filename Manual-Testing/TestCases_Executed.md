# Test Cases

## TC-001 - Login with valid credentials

### Preconditions

- User is on the login page.

#### Test Steps

1. Open the website.
2. Enter a valid username.
3. Enter a valid password.
4. Click the Login button.

## Expected Result

- The user is successfully logged in and redirected to the Products page.

## Actual Result

- User is logged in

## Status

- Pass

## TC-002 - Login with invalid credentials

### Preconditions

- User is on the login page

#### Test Steps

- Open website
- Enter username
- Enter incorrect password
- Click login button
 
## Expected Result

- The user is not logged in, incorrect credentials warning.
- User stays on the login page

## Actual Result
  - user stays logged out

## Status

- failed 

## Possible use cases:

TC-002 - Valid login
Wrong password
Wrong username
Empty usernamev---username is required
Empty password ---username is required
Both fields empty
Username with spaces
Password with spaces
Very long username
Press Enter instead of clicking Login 


# Test Execution Report

| Test Case | Result | Status |
|-----------|--------|--------|
| TC-001 | Successfully logged into the Products page. | PASS |
| TC-002 | Error message displayed for invalid password. | PASS |
| TC-003 | Error message displayed for invalid username. | PASS |
| TC-004 | Error message displayed when fields were empty. | PASS |

