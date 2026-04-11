# 🛍️ Cartly E-Commerce Backend

RESTful Express.js API for a full-featured e-commerce platform. Built with **Node.js, Express, and Sequelize ORM** for flexible database deployment (SQLite, MySQL, or PostgreSQL).

---

## ✨ Features

- ✅ **Product Management** – Browse, search, and filter products
- ✅ **Shopping Cart** – Add/remove items, validate quantities (1-10)
- ✅ **Order Processing** – Create orders with automatic tax calculation (10%)
- ✅ **Delivery Options** – Multiple shipping speeds with dynamic cost calculation
- ✅ **Order Tracking** – Retrieve order history and details
- ✅ **Payment Summary** – Real-time cart total breakdown
- ✅ **Database Flexibility** – SQLite (development) or AWS RDS (production)
- ✅ **Database Reset** – Quick development/testing reset

---

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| **Node.js** | ≥14 | Runtime environment |
| **Express.js** | 4.21.2 | Web framework & routing |
| **Sequelize** | 6.6.5 | ORM for database interaction |
| **SQLite** | (via sql.js) | Default database (development) |
| **CORS** | Built-in | Cross-origin request handling |
| **Nodemon** | Dev | Auto-restart on file changes |
| **ESLint** | Dev | Code quality & style |

**Database Options:**
- Local SQLite (default, zero configuration)
- AWS RDS: MySQL 8.0 or PostgreSQL 12+

---

## 🚀 Quick Start

### Prerequisites
- Node.js v14 or higher
- npm or yarn

### Installation

```bash
# Clone/navigate to backend folder
cd ecommerce-backend

# Install dependencies
npm install

# Start development server
npm start

# Or with auto-reload (watch mode)
npm run dev
