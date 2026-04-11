

```markdown
# 🛍️ Cartly – Full-Stack E-Commerce Platform

A complete, production-ready e-commerce platform with a modern React frontend and scalable Express backend. Perfect for learning full-stack development or as a template for your own e-commerce project.

**🎯 Everything you need:** Product browsing → Shopping cart → Checkout → Order tracking
# 🛍️ Cartly – Full-Stack E-Commerce Platform


### 🎯 Quick Links
- 🌐 **[Live Demo](http://cartly-env.eba-rfxmimnw.ap-southeast-2.elasticbeanstalk.com/)** – Shop & track orders now!
- 📖 **[Backend Documentation](./ecommerce-backend/README.md)**
- 📖 **[Frontend Documentation](./ecommerce-project/README.md)**


---

## 🌟 Key Features

### 🛒 Shopping Experience
- ✅ Browse product catalog with responsive grid
- ✅ Real-time search with debounced filtering
- ✅ Add/remove items from cart with quantity control
- ✅ Multiple delivery speed options with cost calculation

[... rest of README continues as before ...]
---

## 🌟 Key Features

### 🛒 Shopping Experience
- ✅ Browse product catalog with responsive grid
- ✅ Real-time search with debounced filtering
- ✅ Add/remove items from cart with quantity control
- ✅ Multiple delivery speed options with cost calculation

### 💳 Checkout & Payments
- ✅ Order summary with line-item breakdown
- ✅ Automatic tax calculation (10%)
- ✅ Payment summary with total cost
- ✅ One-click place order

### 📦 Order Management
- ✅ Order history with dates and totals
- ✅ Real-time delivery tracking
- ✅ Estimated delivery dates per item
- ✅ Order details view

### 🏗️ Technical Excellence
- ✅ Responsive mobile-first design
- ✅ Fast development with Vite + HMR
- ✅ RESTful API with Express
- ✅ Flexible database (SQLite, MySQL, PostgreSQL)
- ✅ AWS RDS ready for production
- ✅ Error handling & fallback pages

---

## 🏛️ Architecture

**Data Flow:**
1. User interacts with React frontend
2. Frontend calls REST API endpoints (via `/api`)
3. Backend processes requests with Sequelize ORM
4. Database returns data, backend responds with JSON
5. Frontend updates UI with fresh data

---

## 🛠️ Tech Stack

### Frontend
| Technology | Version | Purpose |
|------------|---------|---------|
| React | 19.1.0 | UI framework |
| Vite | 6.3.5 | Build tool & dev server |
| React Router | 7.8.0 | Client-side routing |
| Axios | 1.8.4 | HTTP client |
| DayJS | 1.11.13 | Date formatting |

**Styling:** CSS Modules with responsive design  
**Testing:** Vitest, ESLint

### Backend
| Technology | Version | Purpose |
|------------|---------|---------|
| Node.js | ≥14 | Runtime |
| Express.js | 4.21.2 | Web framework |
| Sequelize | 6.6.5 | ORM |
| SQLite | (sql.js) | Default database |
| CORS | Built-in | Cross-origin requests |

**Databases:** SQLite (dev) or AWS RDS MySQL/PostgreSQL (production)  
**Dev Tools:** Nodemon, ESLint

---

## 🚀 Getting Started

### Prerequisites
- **Node.js** v14 or higher
- **npm** or yarn
- **Git** (optional, for cloning)

### Complete Setup (3 minutes)

#### Step 1: Start the Backend

```bash
# Navigate to backend folder
cd ecommerce-backend

# Install dependencies
npm install

# Start server (runs on port 3000)
npm start

# Or with auto-reload
npm run dev

# Navigate to frontend folder
cd ecommerce-project

# Install dependencies
npm install

# Start dev server (runs on port 5173)
npm run dev


Cartly/
├── ecommerce-backend/          # Express REST API
│   ├── models/                 # Database models (Sequelize)
│   │   ├── Product.js
│   │   ├── CartItem.js
│   │   ├── Order.js
│   │   └── DeliveryOption.js
│   ├── routes/                 # API endpoints
│   │   ├── products.js
│   │   ├── cartItems.js
│   │   ├── orders.js
│   │   ├── deliveryOptions.js
│   │   └── paymentSummary.js
│   ├── defaultData/            # Seed data
│   ├── backend/                # SQLite data files
│   ├── server.js               # Express app entry
│   ├── package.json
│   └── README.md               # Backend documentation
│
├── ecommerce-project/          # React Vite frontend
│   ├── src/
│   │   ├── pages/
│   │   │   ├── home/          # Product browsing page
│   │   │   ├── checkout/      # Checkout page
│   │   │   ├── orders/        # Order history
│   │   │   └── TrackingPage/  # Delivery tracking
│   │   ├── components/        # Reusable UI components
│   │   ├── utils/             # Helper functions
│   │   ├── App.jsx            # Main component & router
│   │   └── main.jsx           # React entry point
│   ├── vite.config.js         # API proxy configuration
│   ├── package.json
│   └── README.md              # Frontend documentation
│
└── README.md                   # This file

