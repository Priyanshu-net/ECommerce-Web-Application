# **E-Commerce Web Application**

This project is an **E-Commerce web application** built using modern web technologies. It provides a platform for users to browse and purchase products online. The application includes various features to enhance the shopping experience.

## **Features**

- **User Authentication**: Secure login and registration system.
- **Product Listings**: Display of products with details such as name, price, and description.
- **Search Functionality**: Users can search for products by name or category.
- **Cart Management**: Add, update, and remove products from the shopping cart.
- **Checkout Process**: Seamless checkout experience with order summary and payment gateway integration.
- **Order Management**: Track order status and view order history.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Payment Gateway**: Integration with Paytm for secure payments.

## **Technologies Used**

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **API**: Fake Store API for product data
- **Payment Gateway**: Paytm

## **Setup Instructions**

- **Clone the repository**:
   ```bash
   git clone https://github.com/Priyanshu-net/ECommerce-Web-Application.git

Navigate to the project directory:
cd ECommerce-Web-Application

- **Install dependencies**:
npm install

- **Configure Paytm**:
Obtain your Paytm Merchant ID and Key from the Paytm Dashboard.
Create a .env file in the root directory and add your Paytm credentials:
PAYTM_MID=your_paytm_merchant_id
PAYTM_KEY=your_paytm_merchant_key
PAYTM_WEBSITE=WEBSTAGING
PAYTM_CHANNEL_ID=WEB
PAYTM_INDUSTRY_TYPE_ID=Retail
PAYTM_CALLBACK_URL=http://localhost:5000/callback

- **Start the development server**:
npm start

## **Usage**
- **Register or log in** to access the application.
- **Browse products** and use the search functionality to find specific items.
- **Add products to the cart** and proceed to checkout.
- **Complete the purchase** using the integrated Paytm payment gateway.
- **Track your orders** and view order history in your account.
## **Contributing**
Contributions are welcome! Please follow these steps to contribute:

## **Fork the repository**.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
## **License**
This project is licensed under the MIT License. See the LICENSE file for details.
