## Functional Test Cases
1	Verify if a user will be able to login with a valid username and valid password.	Positive
2	Verify if a user cannot login with a valid username and an invalid password.	Negative
3	Verify the login page for both, when the field is blank and Submit button is clicked.	Negative
4	Verify the ‘Forgot Password’ functionality.	Positive
5	Verify the messages for invalid login.	Positive
6	Verify the ‘Remember Me’ functionality.	Positive
7	Verify if the data in password field is either visible as asterisk or bullet signs.	Positive
8	Verify if a user is able to login with a new password only after he/she has changed the password.	Positive
9	Verify if the login page allows to log in simultaneously with different credentials in a different browser.	Positive
10	Verify if the ‘Enter’ key of the keyboard is working correctly on the login page.	Positive Other Test Cases
11	Verify the time taken to log in with a valid username and password.	Performance & Positive Testing
12	Verify if the font, text color, and color coding of the Login page is as per the standard.	UI Testing & Positive Testing
13	Verify if there is a ‘Cancel’ button available to erase the entered text.	Usability Testing
14	Verify the login page and all its controls in different browsers	Browser Compatibility & Positive Testing.


## Non-functional Security Test Cases
1	Verify if a user cannot enter the characters more than the specified range in each field (Username and Password).	Negative
2	Verify if a user cannot enter the characters more than the specified range in each field (Username and Password).	Positive
3	Verify the login page by pressing ‘Back button’ of the browser. It should not allow you to enter into the system once you log out.	Negative
4	Verify the timeout functionality of the login session.	Positive
5	Verify if a user should not be allowed to log in with different credentials from the same browser at the same time.	Negative
6	Verify if a user should be able to login with the same credentials in different browsers at the same time.	Positive
7	Verify the Login page against SQL injection attack.	Negative
8	Verify the implementation of SSL certificate.	Positive

## General Test Cases
Check that there are proper validations on Login Page.
Check for an error message if Email, password, or any required field is left blank.
Check the validations on Email and password.
When you log in, check that you stay logged in as you browse products. Also, you need to test the behavior.
When the user doesn’t interact with the site for some time, will the session expire after some time? Make sure the user has been logged out after the session times out.
When you are logged in, log out and make sure you are logged out and that you cannot access any of the accounts pages.
