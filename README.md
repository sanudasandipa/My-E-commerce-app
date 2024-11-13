
# My E-commerce App

An e-commerce application developed with the MERN (MongoDB, Express.js, React, Node.js) stack, designed to provide a smooth online shopping experience. This application includes essential e-commerce functionalities such as product listings, shopping cart, user authentication, and order management.

## Features

- User Authentication with JWT
- Product Listings and Categories
- Shopping Cart Management
- Order Processing
- Integration with Cloudinary for Image Uploads
- Responsive Design


## Technologies Used

**Frontend:** React, HTML, CSS, JavaScript

**Backend:** Node.js, Express.js, MongoDB

**Authentication:** JSON Web Tokens (JWT)

**Image Hosting:** Cloudinary

**Database:** MongoDB

## Installation

1. Clone the repository:

```bash
  git clone https://github.com/sanudasandipa/My-E-commerce-app.git
  cd My-E-commerce-app

```
    

2. Install dependencies for both backend and frontend:

```bash
   # For backend
 cd backend
 npm install

  # For frontend
 cd ../frontend
 npm install

```    

3. Configure environment variables:

4. Start the development server:

```bash
  # Backend (in /backend)
npm start

  # Frontend (in /frontend)
npm start


```  
## Usage

Once the servers are running, you can access the frontend at http://localhost:3000 and the backend at http://localhost:5000 (or as configured).
## API Endpoints

- POST /api/auth/register - Register a new user
- POST /api/auth/login - Login user
- GET /api/products - Retrieve all products
- POST /api/orders - Create an order
## Environment Variables

To run this application, you need to set up the following environment variables in a .env file in the backend directory:

- MONGODB_URI - MongoDB connection string

- TOKEN_SECRET_KEY - Secret key for JWT

- CLOUDINARY_NAME, CLOUDINARY_API_KEY, CLOUDINARY_API_SECRET -    

- Cloudinary configuration for image uploads
## Contributing

If you would like to contribute to this project:

1. Fork the repository.

2. Create a new branch (git checkout -b feature-name).

3. Make your changes.

4. Commit your changes (git commit -m 'Add feature').

5. Push to the branch (git push origin feature-name).

6. Create a Pull Request.
## License
This project is licensed under the MIT License.
[MIT](https://choosealicense.com/licenses/mit/)

