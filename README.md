# Test-Case-Samples
Below are some Test case samples that i wrote while working on previous projects:

**Description:**

Check if the login works when a person uses incorrect user/pass.

**Steps:**

1.Go to www.saucedemo.com

2.Add a incorrect user/pass.

3.Press Login button.

**Expected result:**

User should not be able to login. An error message should be displayed.

**User data:**

User:admin & pass:admin

......................


**Description:**


Check if login works if user enter valid username and invalid password.

**Steps:**

1.Go to www.saucedemo.com

2.Add a valid username

3.Add a invalid password

4.Press Login button


**Expected result:**

User should not be able to login.
Invalid password message should be displayed.


**Test data:**


User:standard_user & Pass:1234

..................

**Description:**


Check response when valid usarname and blank password is entered.


**Steps:**

1.Go to www.soucedemo.com

2.Enter valid usarname.

3.Do not type any password.

4.Press Login button.

**Expected Result:**

User should not be able to login.

Error message should be displayed


.............

## Test Suite : Shopping Cart ##

**Description:**

Verify the functionality of "Add to cart"button.

**Steps:**

1.Go to www.saucedemo.com

2.Login as a valid user with the given credentials.

3.Select any product from the list.

4.Click an Add to cart button

5.Click on"Your cart"icon.


**Expected result:**

Product should be added to the cart

**Test data:**

Username:standard_user
Password:secret_sauce

.................

**Description:**

Check if user is able to change the quantity of a item from cart.

**Steps :**

1.Login with valid credentials.

2.Select any product from list.

3.Click "add to card"button.

4.Click on "cart" icon.

5.Click on "remove" button besides the item.

**Expected results:**

The item should be removed from cart


..............

**Description:**


Verify if the shopping cart accepts 1 item to be added

**Preconditions:**

Shopping cart is empty

**Steps:**

1	Go to product list	

2	Select 1 item	

3	Click "Add to cart" button	

4	Go to shopping cart	


**Expected Results:**

The shopping cart should contain 1 item

...............

**Description:**

Verify if the shopping cart accepts 60 items.


**Preconditions:**

Shopping cart empty

**Steps**:	

1	Go to product list.

2	Add to cart 60 items.

4	Go to shopping cart.

**Expected Results:**

Shopping cart should contain 60 items










