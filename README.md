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


