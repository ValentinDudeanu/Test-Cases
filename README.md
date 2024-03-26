## Test-Cases

Below are some Test Case samples that i wrote while working on previous projects.

-------

***Description:***
Check if the login works when a person uses a correct user/pass.

***Steps to reproduce:***
1. Go to https://auth.emag.ro/user/login.
2. Add a correct email/pass.
3. Press login button.

***Expected results:***
User shoud be able to login and is takes to his profile page.

***Test Data:***
User: Vali & Pass: 123456

-----

***Description:***
Check if forgot password functionality works as expected and an email with resset password link is sent.

***Steps to reproduce:***
1. Go to https://auth.emag.ro/user/login.
2. Add an email adress.
3. Press "continue" button.
4. Press "forgot password".

***Expected results:***
User shoud recieve an email with a resset password link. That link shoud allow the user to create a new password.

***Test Data:***
User: Vali & Pass: 123456

-------

***Description:***
Check if login works when a person uses whrong credetials

***Steps to reproduce:***
1. Go to https://auth.emag.ro/user/login.
2. Add an email adress that doen't exist.
3. Press "continue" button.
4. Press a whrong password.
5. Press "continue" button.

***Expected results:***
User shoud recieve an notification that he entered the whrong credentials.

***Test Data:***
User: dudeanu.valentin1@gmail.com & Pass: 123456TT

-------

***Description:***
Check if login works when a person uses no credetials.

***Steps to reproduce:***
1. Go to https://auth.emag.ro/user/login.
2. Press "continue" button without insering any credentials.

***Expected results:***
User shoud recieve an notification that he entered no credentials. 

***Test Data:***
User: - 

-------

***Description:***
Check if search bar works when a user want's to search specific for an product.

***Steps to reproduce:***
1. Go to https://emag.ro.
2. Press "search bar'.
3. Insert product name.
4. Press "enter".

***Expected results:***
User is taken to product page where it shown the product he's looking for.

***Test Data:***
User: - 

-----

***Description:***
Check if the "search bar" is able to auto-complet a product after entering first 3-4 letters.

***Steps to reproduce:***
1. Go to https://emag.ro.
2. Press "search bar'.
3. Insert first 3 letters of a product.
4. Press "enter".

***Expected results:***
User shoud be given the full name of the product he's looking for or similar products that starts with those letters.

***Test Data:***
User: - 

------

***Description:***
Check if when a user enters a product that doesn't exist it gives other options.

***Steps to reproduce:***
1. Go to https://emag.ro
2. Press "search bar'
3. Insert first 3 letters of a product.
4. Press "enter"

***Expected results:***
User shoud be given other options regarding the product he's looking for.

***Test Data:***
User: - 

------

***Description:***
Check if sign up works using an valid email.

***Steps to reproduce:***
1. Go to budgetmanager.com/signup.
2. Add a correct email.
3. Create a password
4. Confirm password
5. Press "sign-up" button.

***Expected results:***
User shoud have an new account am taken to home page.

***Test Data:***
User: dudeanu.valentin@gmail.com & Pass: DV123456

------

***Description:***
Check if sign up works while leaving the email field empty.

***Steps to reproduce:***
1. Go to budgetmanager.com/signup.
2. Create a password
3. Confirm password
4. Press "sign-up" button.

***Expected results:***
User shoud recieve a notification that he has to enter an email.

***Test Data:***
Pass: DV123456

----------

***Description:***
Check if sign up works while leaving the password field .

***Steps to reproduce:***
1. Go to budgetmanager.com/signup.
2. Add a correct email.
3. Add a password to "reconfirm password" field
4. Press "sign-up" button.

***Expected results:***
User shoud recieve a notification that he has to enter a password.

***Test Data:***
User: dudeanu.valentin@gmail.com

---------

***Description:***
Check if sign up works while leaving the "reepassword" field empty.

***Steps to reproduce:***
1. Go to budgetmanager.com/signup.
2. Add a correct email.
3. Create a password
4. Press "sign-up" button.

***Expected results:***
User shoud recieve a notification that he has to fill the "reepassword" field.

***Test Data:***
User: dudeanu.valentin@gmail.com & Pass: DV123456

--------

***Description:***
Check if sign up works while having a different password from confirm password.

***Steps to reproduce:***
1. Go to budgetmanager.com/signup.
2. Add a correct email.
3. Create a password
4. Confirm with a different password
5. Press "sign-up" button.

***Expected results:***
User shoud recieve a notification that he has fill the repassword different

***Test Data:***
User: dudeanu.valentin@gmail.com & Pass: DV123456

-------

***Description:***
Check if sign up works using an already taken email

***Steps to reproduce:***
1. Go to budgetmanager.com/signup.
2. Add a already taken email.
3. Create a password
4. Confirm password
5. Press "sign-up" button.

***Expected results:***
User shoud recieve a notification that the email is already taken.

***Test Data:***
User: dudeanu.valentin@gmail.com & Pass: DV123456

-----------

***Description:***
Check if sign-in works witn invalid email adress

***Steps to reproduce:***
1. Go to budgetmanager.com/login.
2. Add an invalid email.
3. Add a correct password
4. Press "sign-in" button.

***Expected results:***
User shoud recieve a notification that he entered an invalid email.

***Test Data:***
User: dudeanu.valentin1@gmail.com & Pass: DV123456

--------

***Description:***
Check if sign-in works witn empty email field

***Steps to reproduce:***
1. Go to budgetmanager.com/login.
2. Add a correct password
3. Press "sign-in" button.

***Expected results:***
User shoud recieve a notification that you have to enter an email adress.

***Test Data:***
Pass: DV123456

----------

***Description:***
Check if sign-in works witn empty password field

***Steps to reproduce:***
1. Go to budgetmanager.com/login.
2. Add an valid email adress.
3. Press "sign-in" button.

***Expected results:***
User shoud recieve a notification that you have to enter a password.

***Test Data:***
User: dudeanu.valentin1@gmail.com & Pass: DV123456

------------

***Description:***
Check if show password functionality works

***Steps to reproduce:***
1. Go to budgetmanager.com/login.
2. Add an invalid email.
3. Add a correct password
4. Press "show password" button.

***Expected results:***
User shoud see the password that he entered.

***Test Data:***
User: dudeanu.valentin1@gmail.com & Pass: DV123456










