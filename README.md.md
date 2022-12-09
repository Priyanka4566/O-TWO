This is ReadMe for our project

//Project Name: O_Two 
//Course Name: Distributed Computing (CEG-7370-90)
//Professor Name: Ashutosh Shivakumar
//Team Name: Gryffindor
//Date:12/09/2022
//Technologies used: Python, Django, SQLite, bootstrap.

# A brief description about project: 
In this project we worked on building a model that will be able to provide oxygen cylinders to everyone through online website.

## FUNCTIONALITY & FEATURES:

1.	Admin has the ability to modify the products list. He has the ability to change the prices and/or add/remove products.
	We created this model called product in models.py.
2.	The administrator can label an order as "confirmed," "shipped," or "delivered" after viewing the specifics of the ordered items.
3.	On the login page, users can quickly sign in or register.
4.	We developed the search view function in views.py to search products. We can skim the products using this feature to find the one we want.
5.	The item will be added to the cart after you click "add to cart."
6.	As the user shops, the price and number of items in their cart are updated. The user can view their entire shopping cart with a detailed price on the cart page.
7.	On the following screen, enter your address, then click the payment button to be taken to the payment page. 
8.	The admin will validate your order from the admin panel side, after verifying the transaction's success.
9.	Your order will be placed in front end as soon as the payment is received.

## How to Setup:

To ensure a good setup, follow to these easy steps:
1.	First Clone the repository to preserve directory structure
	(link)
2.	Open Command Prompt (cmd) in your code editor, if you have one, and navigate to the location where you cloned this repository.
3.	This command should be run in cmd:
	Pip install -r requirements.txt
4.	Install all the libraries manually if that doesn't work using the following commands: 
	Pip install Django
	Pip install Django-widget-tweaks
	Pip install sqlparse
	Pip install pillow
5.	Python manage.py migrate will carry out the necessary migrations after the following command.
6.	Run the python manage.py run server command after installing libraries.
7.	A http link such as e.g. 127.0.0.1:8000 will appear.
8.	You can view the newly developed website if you copy and paste this link into your browser.
9.	Cheers !! 

	If you face any problem like script not running in environment or anything. You can raise an issue in GitHub, we will help you to sort it out  thank you.

    ## Deployment:

After developing the code locally, we set up EC2 in AWS to host it in the cloud in zip file. After configuring the website and installing instances, the website link is presented, and clicking it launches the locally developed website.
