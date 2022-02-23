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
    a. The user select the login button.
    b. The system shows the login page.
    c. The user click login.
    d. The system shows the Login options.
    e. The user input their own account.
    f. The user input the passport.
    g. The system shows the success, and go to the homepage.
2. Did not have an account:
    a. The user select create a new account.
    b. The system shows the create account page.
    c. User input their Email and passport.
    d. System record the information.
    e. System shows create account successful.

**Postconditions:** <br>
1. Only authorized accounts can login.
2. After login, each account can only operate the functions that obtain the permission.
