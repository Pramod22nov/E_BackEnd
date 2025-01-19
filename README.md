# E_BackEnd
 
Features
Signup: Register a new user.
Login: Authenticate and log in the user.
Get/View Profile: Fetch the user's profile.
Add to Cart: Add products to the user's cart.
Checkout: Checkout the cart by deducting stock.
Place Order: Place an order after checkout and clear the cart.
Logout: Log out the user.
Prerequisites
Before setting up the project, ensure that the following are installed:

Node.js
MongoDB - Ensure MongoDB is running locally or on a cloud service like MongoDB Atlas.
Postman API testing tool.
Before running it locally, change or create a .env file in root directory:

PORT=5000
MONGO_URI=your_url
JWT_SECRET=your_jwt_secret

Run Locally
git clone <repository-url>
cd E_Backend
npm install
npm start
