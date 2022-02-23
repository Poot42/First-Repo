# Use case Name: Login to the system

**ID:** 2<br>
**Priority:** High<br>
**Actor:** User<br>
**Description:** All user use their own account login into the system to use this system.<br>
**Trigger:** The user wants to use the system.<br>
**Type:** External<br>
**Preconditions:** The user who has a system account.<br>
**Normal Course:**<br>
1. Already had an account:
    1. The user select the login button.
    2. The system shows the login page.
    3. The user click login.
    4. The system shows the Login options.
    5. The user input their own account.
    6. The user input the passport.
    7. The system shows the success, and go to the homepage.
2. Did not have an account:
  1. The user select create a new account.
  2. The system shows the create account page.
  3. User input their Email and passport.
  4. System record the information.
  5. System shows create account successful.

**Postconditions:** <br>
1. Only authorized accounts can login.
2. After login, each account can only operate the functions that obtain the permission.
