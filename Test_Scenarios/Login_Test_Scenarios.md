# Test Scenarios – Login Functionality

## Positive Scenarios
1. Verify login with valid email and valid password
2. Verify user is redirected to the secure area after successful login
3. Verify logout functionality after successful login

## Negative Scenarios
4. Verify login with valid email and invalid password
5. Verify login with invalid email and valid password
6. Verify login with invalid email and invalid password
7. Verify error message when email field is empty
8. Verify error message when password field is empty
9. Verify error message when both email and password fields are empty

## UI & Validation Scenarios
10. Verify email field accepts valid email format
11. Verify password field masks the entered characters
12. Verify error messages are clear and user-friendly
13. Verify login button is disabled when required fields are empty

## Security Scenarios (Basic)
14. Verify system does not allow login without authentication
15. Verify user session is terminated after logout
