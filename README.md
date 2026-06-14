# InventoryFlow-
Inventory Management Dashboard--A full-stack Inventory Management Dashboard built with Next.js, TypeScript, Node.js, PostgreSQL, AWS, and Tailwind CSS. The application enables businesses to efficiently manage products, inventory levels, suppliers, and sales through a modern analytics dashboard.

## 🚀 Features

### Inventory Management

* Create, update, and delete inventory items
* Track stock levels in real time
* Manage product categories and inventory status
* Low-stock monitoring and inventory alerts

### Supplier Management

* Add and manage supplier information
* Track supplier-product relationships
* Maintain supplier contact details

### Sales Tracking

* Record and monitor sales transactions
* Analyze revenue trends
* View sales performance metrics

### Dashboard Analytics

* Inventory overview dashboard
* Product performance insights
* Sales analytics and reporting
* Visual data representation using charts

### Search & Filtering

* Product search functionality
* Category-based filtering
* Inventory status filtering
* Supplier-based search

### Cloud Deployment

* Backend deployed on AWS EC2
* PostgreSQL database hosted on AWS RDS
* File and image storage using AWS S3

---

## 🛠️ Tech Stack

### Frontend

* Next.js
* TypeScript
* Tailwind CSS

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* PostgreSQL

### Cloud & DevOps

* AWS EC2
* AWS RDS
* AWS S3

### Development Tools

* Git
* GitHub
* Postman

---

## 📂 Project Structure

```bash
InventoryFlow/
│
├── client/                          # Next.js Frontend
│
│   ├── public/
│   │   ├── next.svg
│   │   └── vercel.svg
│   │
│   ├── src/
│   │   ├── app/
│   │   │
│   │   ├── (components)/
│   │   │   ├── Header/
│   │   │   ├── Navbar/
│   │   │   ├── Rating/
│   │   │   └── Sidebar/
│   │   │
│   │   ├── dashboard/
│   │   │   ├── CardExpenseSummary.tsx
│   │   │   ├── CardPopularProducts.tsx
│   │   │   ├── CardPurchaseSummary.tsx
│   │   │   ├── CardSalesSummary.tsx
│   │   │   ├── StatCard.tsx
│   │   │   └── page.tsx
│   │   │
│   │   ├── products/
│   │   │   ├── CreateProductModal.tsx
│   │   │   └── page.tsx
│   │   │
│   │   ├── inventory/
│   │   ├── expenses/
│   │   ├── settings/
│   │   ├── users/
│   │   ├── dashboardWrapper.tsx
│   │   ├── redux.tsx
│   │   ├── layout.tsx
│   │   └── page.tsx
│   │
│   └── state/
│       ├── api.ts
│       └── index.ts
│
├── server/                          # Node.js Backend
│
│   ├── src/
│   │   ├── controllers/
│   │   │   ├── dashboardController.ts
│   │   │   ├── expenseController.ts
│   │   │   ├── productController.ts
│   │   │   └── userController.ts
│   │   │
│   │   ├── routes/
│   │   │   ├── dashboardRoutes.ts
│   │   │   ├── expenseRoutes.ts
│   │   │   ├── productRoutes.ts
│   │   │   └── userRoutes.ts
│   │   │
│   │   └── index.ts
│
│   ├── prisma/
│   │   ├── schema.prisma
│   │   ├── seed.ts
│   │   ├── migrations/
│   │   └── seedData/
│   │
│   ├── assets/
│   │   ├── logo.png
│   │   ├── product images
│   │   └── profile image
│   │
│   └── ecosystem.config.js
│
├── README.md
└── package configuration files
```

## 🔐 Key Functionalities

* Authentication and Authorization
* Product Inventory Management
* Supplier Management
* Sales Monitoring
* Data Visualization
* Cloud-Based File Storage
* Responsive Dashboard Design
* REST API Architecture

---

## 📈 Future Enhancements

* Role-Based Access Control (RBAC)
* Inventory Forecasting
* Email Notifications
* Automated Reorder Suggestions
* Export Reports (PDF/Excel)
* Multi-Warehouse Support
* Docker Containerization
* CI/CD Pipeline Integration

---

## 🎯 Learning Outcomes

This project helped strengthen knowledge in:

* Full Stack Development
* REST API Design
* Database Design and Modeling
* PostgreSQL Query Optimization
* AWS Cloud Deployment
* Dashboard Development
* Data Visualization
* Software Engineering Best Practices

---

## 👨‍💻 Author

**Jahanvi Bagjani**

* LinkedIn: https://linkedin.com/in/jahanvi-bagjani-400390314
* GitHub: https://github.com/JAHANVI88
