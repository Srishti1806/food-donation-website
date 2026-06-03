# 🍽️ Food Donation Website

A complete MERN stack web application for managing food donations between hotels, restaurants, and NGOs.

## 📋 Quick Start

### 1. Backend Setup
```bash
npm install
cp .env.example .env
npm run server
```

### 2. Frontend Setup
```bash
cd client
npm install
npm start
```

Visit: http://localhost:3000

## 🎯 Features Implemented

✅ **Authentication & Authorization**
- User registration and login
- JWT token-based authentication
- Role-based access control (RBAC)
- Admin approval workflow

✅ **Hotel/Restaurant Features**
- Create food donations
- Manage donation listings
- Track donation status
- View NGO claims

✅ **NGO Features**
- Browse available donations
- Claim donations
- Track donation status
- Mark as picked up & completed

✅ **Admin Features**
- Approve/reject organizations
- Monitor all donations
- View statistics dashboard
- Manage approved NGOs

## 🗄️ Database Schema

- **User**: Hotels, Restaurants, NGOs, Admin
- **Donation**: Food donations with status tracking
- **Admin**: Approval management & statistics

## 🔐 Security

- Password hashing with bcryptjs
- JWT authentication (24h expiry)
- Role-based authorization
- CORS protection

## 📱 Tech Stack

**Frontend**: React, Tailwind CSS, Axios
**Backend**: Node.js, Express, MongoDB, Mongoose

---

**Happy Coding! 🚀**