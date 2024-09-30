/api/bookings/
/api/registration/# Readme.txt
Base URL: https://api.example.com/
1. User Management
Register a New User
Path: /api/v1/users/register
Method: POST
Description: Registers a new user in the system.
Required Parameters:
username (String)
password (String)
email (String)
Login
Path: /api/v1/users/login
Method: POST
Description: Logs in an existing user.
Required Parameters:
username (String)
password (String)
2. Product Management
Get Product List
Path: /api/v1/products
Method: GET
Description: Retrieves the list of all available products.
Add a New Product
Path: /api/v1/products
Method: POST
Description: Adds a new product to the system.
Required Parameters:
name (String)
price (Decimal)
description (String)
3. Orders
Create a New Order
Path: /api/v1/orders
Method: POST
Description: Creates a new order.
Required Parameters:
userId (String)
productIds (Array of Strings)
quantity (Integer)

