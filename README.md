🌱 Agrilink — Direct Farm Marketplace

A modern full-stack marketplace platform designed to connect local farmers directly with consumers without middlemen.
Built with the MERN stack, the platform supports secure authentication, product management, order tracking, reviews, and role-based dashboards for customers, farmers, and administrators.

🚀 Built With
Frontend
React.js
Tailwind CSS
Framer Motion
Backend
Node.js
Express.js
Database
MongoDB
Mongoose ODM
Authentication & Security
JWT Authentication
bcrypt Password Hashing
📂 Folder Structure
HarvestHub/
│
├── backend/
│   ├── src/
│   │   ├── config/
│   │   │   └── db.js
│   │   │
│   │   ├── controllers/
│   │   │   ├── authController.js
│   │   │   ├── productController.js
│   │   │   ├── orderController.js
│   │   │   ├── reviewController.js
│   │   │   └── farmerController.js
│   │   │
│   │   ├── middleware/
│   │   │   ├── auth.js
│   │   │   ├── upload.js
│   │   │   └── errorHandler.js
│   │   │
│   │   ├── models/
│   │   ├── routes/
│   │   └── server.js
│   │
│   ├── uploads/
│   └── .env
│
└── frontend/
    └── src/
        ├── components/
        ├── context/
        ├── pages/
        ├── hooks/
        ├── services/
        └── utils/
⚙️ Requirements

Before running the project, make sure you have:

Node.js (v18 or above)
MongoDB Community Server or Atlas
npm / yarn
🛠️ Installation Guide
1️⃣ Clone the Repository
git clone https://github.com/your-username/harvesthub.git
cd harvesthub
2️⃣ Backend Setup
cd backend
npm install

Create a .env file inside the backend folder:

PORT=5000
MONGO_URI=mongodb://localhost:27017/harvesthub
JWT_SECRET=your_secret_key
JWT_EXPIRE=7d
NODE_ENV=development

Start backend server:

npm run dev
3️⃣ Frontend Setup
cd ../frontend
npm install
npm start

Frontend will run on:

http://localhost:3000
🔑 Core Features
👨‍🌾 Farmer Dashboard
Add / edit / delete products
Manage customer orders
Upload product images
View analytics & sales stats
🛒 Customer Features
Browse products
Search & filter items
Add to cart
Wishlist support
Place and track orders
Product reviews & ratings
👑 Admin Panel
Manage all users
Monitor orders
Access platform statistics
Remove fraudulent listings/users
🔐 Authentication System
JWT-based login/signup
Protected routes
Role-based authorization
Password encryption using bcrypt
📦 API Overview
Authentication
POST   /api/auth/register
POST   /api/auth/login
GET    /api/auth/me
PUT    /api/auth/profile
Products
GET    /api/products
GET    /api/products/:id
POST   /api/products
PUT    /api/products/:id
DELETE /api/products/:id
Orders
POST   /api/orders
GET    /api/orders/my
GET    /api/orders/:id
PUT    /api/orders/:id/status
Reviews
POST   /api/reviews/product/:productId
GET    /api/reviews/product/:productId
DELETE /api/reviews/:id
Cart
GET    /api/cart
POST   /api/cart
PUT    /api/cart/:productId
DELETE /api/cart/:productId
✨ Highlights
🌗 Dark / Light Theme
📱 Fully Responsive UI
⚡ Smooth Framer Motion Animations
🔎 Advanced Product Filtering
🔔 Notification System
❤️ Wishlist Functionality
📸 Multer Image Upload Support
📊 Dashboard Analytics
🛡️ Secure REST APIs
📸 Future Improvements
Online payment integration
Real-time order tracking
Chat system between farmers & buyers
AI-based crop/product recommendations
Multi-language support
🤝 Contribution

Contributions, suggestions, and improvements are welcome.

Fork the repository
Create a feature branch
Commit your changes
Open a pull request
📄 License

This project is licensed under the MIT License.

👨‍💻 Developer

Developed as a full-stack MERN marketplace project focused on improving direct farmer-to-customer accessibility and digital agriculture solutions.
