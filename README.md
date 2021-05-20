# Check-List for Log In, Sign Up, Forgot Password on Facebook

# General:
* Smoke:Open web site facebook.com;
# Sign Up
 Smoke checks:
* Check whether the registration form opens by clicking on the "Create account" button;
* Fill in all fields with valid data (In the field for mobile phone or mail, enter the valid phone number) and click the Register button;
* Fill in all fields with valid data (In the field for mobile phone or mail, enter the valid Email) and click the Register button;

Critical Path checks:
* Fill out only the "Name" and "surname" field and click the "Registration" button (Check if the message appears about the missed required fields);
* Fill out only the "mobile number" field and click the "Registration" button (Check if the message appears about the missed required fields);
* Fill out only the "date birth" field and click the "Registration" button (Check if the message appears about the missed required fields);
* Select any gender and click "Registration" button (Check if the message appears about the missed required fields);
* Fill in all the fields with valid data and in the field "entering the phone number or Email" enter the phone number using the prefix "80 ..." and Click "Registration" button;
* Fill in all the fields with valid data and in the field "entering the phone number and Email" enter Email without dot in the domain part and Click "Registration" button;
* Fill in all the fields with valid data and in the "Password" field insert 5 digits and Click "Registration" button;
* Fill in all the fields with valid data and in the "Password" field insert 8 digits and 8 symbols (Ex. !,&,?) and Click "Registration" button;
* In the "Gender" field, select "Other" and check whether each item is selected in the pop-up menu.
* Check if information opens when you click on the "Conditions" links "Data Use Policy" and "Cookie File Policy";
* Click on the Cross burron.

Extended checks:
* Insert in the "Name" and "Username" fields digits;
* Insert in the "Name" and "Username" HTML code;
* In the field of birth, choose the last year (1905);
* Check whether the hint appears when you click on the "?";
* * Fill in all the fields with valid data and in the field "entering the phone number and Email" enter Email without domain part and Click "Registration" button;
* Fill in all the fields with valid data and in the field "entering the phone number and Email" enter Email without symbol "@" and Click "Registration" button;
* Press the space around the "Registration" button;
* Check whether it is possible to create an account by completing all fields by data from the already created account;
* Check page for grammatical errors.

# Login In

 Smoke Checks:
 * Check if there is an input form by clicking (https://www.facebook.com);
 * Check if there is an input to the previously created account by entering a valid mail and password.

Critical Path Checks:
* Fill only Email field with valid Email and click "Log In" button;
* Enter the core email address and invalid password and click "Login" button;
* Enter the valid number (if it is recorded) and password and click "Login" button;
Extended Checks:
* Leave all the fields empty and click on the "Login" button and click "Login" button;
* Enter Email without a domain part and insert valid password and click "Login" button;
* Enter Email without a symbol "@" and insert valid password and click "Login" button;
* Enter Email without a dot in the domain part and insert valid password and click "Login" button;
* Enter the phone number without the last 2 or 1 numbers and enter the vaid Password after that Press the "Login" button;
* Check page for grammatical errors.

# Forgot password
  Smoke checks:
 * Click on the "forgot password" button, Check whether the form opens.
 * Enter your mobile phone number or email address you created acc and click "Search" button;
  
  Critical Path: 
* * Enter Email without a domain part and click "Search" button;
* Enter Email without a symbol "@" and click "Search" button;
* Enter Email without a dot in the domain part and click "Search" button;
* Enter the phone number without the last 2 or 1 numbers and click "Search" button;
* When entering a valid mail or phone number, check if the references to the recovery of Accuaut come;
* Enter the phone number using the prefix "+375" and "80" and click "Search" button;
* Click on the "cancel" button.

 Extended Checks:
 * Enter any characters (Ex. "!@#$%^&*?") and click "Search";
 * Insert HTML code and click "Search" button;
 * Leave the field empty and click "Search" button;
 * Check page for grammatical errors.
