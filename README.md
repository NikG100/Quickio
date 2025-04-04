Quickio - E-commerce Platform

Quickio is a full-fledged e-commerce platform built with React.js, Tailwind CSS, Node.js, and MongoDB. It provides users with a seamless shopping experience, secure authentication, and an intuitive admin panel for product management.

Features

User Features:

🔑 Authentication: JWT-based authentication (Access & Refresh Tokens)

🛒 Cart & Wishlist: Save products for later purchases

🔍 Product Search: Fast, debounced search functionality

📦 Product Browsing: Explore products by categories and subcategories

📧 Password Recovery: Reset password functionality

📱 Fully Responsive: Optimized for all screen sizes

Admin Features:

🏗️ Product Management: Add, update, delete products

📂 Category & Subcategory Management: Organize products efficiently

📊 Dashboard: View analytics and manage orders

Tech Stack

Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js, MongoDB

Authentication: JWT (Access & Refresh Tokens)

Database: MongoDB with Mongoose ORM

Installation & Setup

Prerequisites

Ensure you have the following installed:

Node.js

MongoDB

Clone the Repository

git clone https://github.com/yourusername/quickio.git
cd quickio

Backend Setup

cd backend
npm install
npm start

Frontend Setup

cd frontend
npm install
npm start

Environment Variables

Create a .env file in the backend directory and configure:

MONGO_URI=your_mongo_db_uri
JWT_SECRET=your_secret_key

Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request.