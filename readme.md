Test Steps and Details
Step No.	Test Step Description	Expected Result	Test Data
1	Open the Gmail login page.	Gmail login page is displayed with fields for email/phone, password, and a "Next" button.	N/A
2	Enter a valid email address and click "Next".	The password input page is displayed.	Email: validuser@gmail.com
3	Enter a valid password and click "Next".	User is successfully logged in and redirected to the Gmail inbox.	Password: ValidPassword123
4	Enter an invalid email address and click "Next".	An error message "Couldn't find your Google Account" is displayed.	Email: invaliduser@gmail.com
5	Enter a valid email but incorrect password and click "Next".	An error message "Wrong password. Try again or click Forgot password to reset it." is displayed.	Email: validuser@gmail.com, Password: WrongPass123
6	Leave the email field empty and click "Next".	An error message "Enter an email or phone number" is displayed.	Email:
7	Leave the password field empty after entering a valid email and click "Next".	An error message "Enter your password" is displayed.	Email: validuser@gmail.com, Password:
8	Test login with an email format but without a domain and click "Next".	An error message "Enter a valid email address" is displayed.	Email: username@
9	Verify "Forgot email?" functionality.	User is redirected to the "Find your email" page.	N/A
10	Verify "Forgot password?" functionality.	User is redirected to the password recovery page after entering the email.	Email: validuser@gmail.com
11	Test login functionality with account locked due to multiple failed attempts.	An error message "Account temporarily locked. Try again later." is displayed.	Email: validuser@gmail.com, Password: InvalidPassword
