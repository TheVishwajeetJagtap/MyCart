# MyCart
MyCart is python command line interface based(CLI) E-commerce application.


 	MyCart E-commerce app
   
> Steps to run the app

>	Note: For this assignment, I used the MySQL Database.

1.	Create a virtualenv using >>>virtualenv -p python3 <venv_name>
2.	Activate the venv using >>>source <venv_name>/bin/activate
3.	Install the requirements using >>>pip install -r requirements.txt
4.	Install the current codebase using, >>>python setup.py develop
5.	Do the necessary changes like database user & password in mycart/app_config.py

> User App (Flow-1)
1.	To run the user app (i.e. customer) navigate to MyCart/mycartapp/user then run the main.py using >>>python main.py
2.	Once the app is running, the menu list will be shown.
3.	Option 1 will display the all available product categories.
4.	Option 2 will display the products category wise by entering the category id.
5.	Option 3 will display the product details by entering the product id.
6.	Option 4 is for, adding the product to the cart, need to enter the product id once the choice is selected.
7.	Option 5 will display the products list which is added in cart.
8.	Option 6 is for removing the product from cart, need to enter the product id once the choice is selected.
9.	Option 7 is for generating the bill, need to enter the user's name for billing generation process once the choice is selected.

> Admin App (Flow-2)
1.	to run the app (admin app), navigate to >>>MyCart/mycartapp/admin
1.	then run the main.py using >>>python main.py
2.	Once the app the app is running, the menu list will be shown.
3.	Option 1 is for adding the new brand product category, need to enter category name, once the choice is selected.
4.	Option 2 is adding the new brand product, need to enter product name, once the choice is selected, after it will ask for 'product name', then it will ask for the product price. then it will ask for product description, here the product description is taken in dictionary (key : value format), so firstly we need to specify numbers of fields, according it will ask for the key & value.
5.	Option 3 is for displaying the user cart details.
6.	Option 4 is for, displaying the bills generated by the user.
