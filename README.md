# 🌱 HarvestHub — Direct Farm Marketplace

A modern full-stack marketplace platform designed to connect local farmers directly with consumers without middlemen.

Built using the MERN stack, the platform includes secure authentication, product management, order tracking, reviews, and dedicated dashboards for customers, farmers, and admins.

---

# 🚀 Tech Stack

## Frontend
- React.js
- Tailwind CSS
- Framer Motion

## Backend
- Node.js
- Express.js

## Database
- MongoDB
- Mongoose

## Authentication
- JWT Authentication
- bcrypt Password Hashing

---

# 📂 Project Structure

```bash
HarvestHub/
│
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
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
```

---

# ⚙️ Requirements

Before running the project, make sure you have:

- Node.js v18 or above
- MongoDB Community Server or Atlas
- npm or yarn

---

# 🛠️ Installation

## 1. Clone Repository

```bash
git clone https://github.com/your-username/harvesthub.git
cd harvesthub
```

---

## 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/harvesthub
JWT_SECRET=your_secret_key
JWT_EXPIRE=7d
NODE_ENV=development
```

Start backend server:

```bash
npm run dev
```

---

## 3. Frontend Setup

```bash
cd ../frontend
npm install
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

# ✨ Features

## 👨‍🌾 Farmer Dashboard
- Add / edit / delete products
- Manage customer orders
- Upload product images
- View analytics & sales stats

## 🛒 Customer Features
- Browse products
- Search & filter items
- Add to cart
- Wishlist support
- Place and track orders
- Product reviews & ratings

## 👑 Admin Panel
- Manage users
- Monitor orders
- Platform analytics
- Remove fraudulent listings

---

# 🔐 Authentication

- JWT-based login/signup
- Protected routes
- Role-based authorization
- Password encryption using bcrypt

---

# 📦 API Endpoints

## Authentication

```http
POST   /api/auth/register
POST   /api/auth/login
GET    /api/auth/me
PUT    /api/auth/profile
```

## Products

```http
GET    /api/products
GET    /api/products/:id
POST   /api/products
PUT    /api/products/:id
DELETE /api/products/:id
```

## Orders

```http
POST   /api/orders
GET    /api/orders/my
GET    /api/orders/:id
PUT    /api/orders/:id/status
```

## Reviews

```http
POST   /api/reviews/product/:productId
GET    /api/reviews/product/:productId
DELETE /api/reviews/:id
```

## Cart

```http
GET    /api/cart
POST   /api/cart
PUT    /api/cart/:productId
DELETE /api/cart/:productId
```

---

# 🌟 Highlights

- 🌙 Dark / Light Mode
- 📱 Fully Responsive UI
- ⚡ Smooth Framer Motion Animations
- 🔍 Product Search & Filters
- 🔔 Notification System
- ❤️ Wishlist Support
- 📸 Multer Image Uploads
- 📊 Dashboard Analytics
- 🛡️ Secure REST APIs

---

# 🚀 Future Improvements

- Online payment integration
- Real-time order tracking
- Farmer-buyer chat system
- AI crop recommendations
- Multi-language support

---

# 🤝 Contribution

Contributions and suggestions are welcome.

```bash
Fork the repository
Create a feature branch
Commit your changes
Open a pull request
```

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Developer

Built as a full-stack MERN marketplace project focused on improving direct farmer-to-customer accessibility and digital agriculture solutions.
