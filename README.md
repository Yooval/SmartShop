## Overview

**SmartShop** is an e-commerce web application store. 
The website is built using Spring Boot for server side and Angular, Typescript and bootstrap for client side. It connects to a MySQL database.

- ### View demonstration of the application  [here](https://drive.google.com/file/d/1SjZIevcSebYJPZ6wJRV1J4cuMmXBxj8e/view?usp=drive_link). See how it works!


### Client Side:

  - **Login Page**: Allows users to log in with their Okta credentials in order to see all their transactions.
  - **Books/Coffee Mags/Mouse pads/Luggage Tags  Pages**: Different deparments in store where you can view all product and add them to cart
  - **Search Button**: Allow users to filter products by keywords. 
  - **Logout/ Member/ Orders Buttons (logged users only)**: buttons that allows you to logout, check discounts for members and view all your orders.
  - **Cart icon**: direct you to a checkout form.
  
### Server Side:
The server side handles two main responsibilities:
- Stores and retrieves data: Manages products, users, orders, and payments.
- Handles checkout and payments: Processes orders and validates payment information.

### Installation:
- create yout okta acount for registration [here](https://developer.okta.com/login/).
- open the Server-Side and run it from file **SpringBootEcommerceApplication**.
- open the Client-Side and run the command **npm start -- --configuration=qa**. You should see the app running on https://localhost:4200.

