This is React-based online store application where users can register, log in, browse products, add them to their cart, and view their cart. The app uses Redux for state management and localStorage for user authentication and persistence.

## Features
 ### User Authentication

    Register and log in functionality using localStorage.
    Protected routes to prevent unauthorized access to certain pages.
    Users are redirected to the login page if not authenticated.

### Product Listing

   A catalog of products displayed on the Products Page.
    Add products to the cart from the product listing.

### Shopping Cart

    View items in the cart, update quantities, and remove items.
    Calculate the total price of items in the cart.

### Persistent State
    
    LocalStorage is used to save the user session and cart data.
## Installation
1.	Clone the repository:
Git clone https://github.com/shamindi08/reactfoodcity.git
cd reactfoodcity
2.	npm install
`npm install react-router-dom`
`npm install @reduxjs/toolkit react-redux`
`npm install formic`
`npm install yup`
`npm install prop-types`
3.	Run the app
 ` npm start`
4.	  Mandatory Login: Users must register and log in before they can access the products page or any other protected pages. Navigation to these pages is restricted until the user is authenticated. Attempting to access protected pages without logging in redirects users to the login page.
5.	 Shopping Features:
   After logging in, users can browse products, add products to the cart, and view the cart.
  The cart page allows users to view the items they have added, adjust quantities, remove items, and calculate the total price of all items in the cart.
	
