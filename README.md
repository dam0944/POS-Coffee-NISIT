# Coffee NISIT POS System

A modern, user-friendly Point of Sale (POS) web application for coffee shops. Coffee NISIT streamlines sales, inventory, staff, and reporting operations to help your business run efficiently. This README introduces the system’s features and provides context for internship applications.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Screenshots](#screenshots)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Contact](#contact)

---

## Overview

Coffee NISIT POS System is designed for small to medium-sized coffee shops, enabling staff and managers to easily process sales, manage products, track shifts, handle roles, oversee customers, and generate useful reports—all within a clean and intuitive interface.

---

## Features

- Quick order processing with a visual POS screen
- Invoice management and daily sales tracking
- Customer management and loyalty tracking
- Shift management with profit and balance summaries
- Product inventory and catalog management
- Role-based access control for staff
- Sales reports by user, time, and PDF export
- Export data to Excel for audits or further analysis

---

## Screenshots

### 1. POS (Point of Sale) Screen

Fast, intuitive order-taking interface with a product catalog, real-time cart, and payment actions.

![image1](image1)

---

### 2. Invoice Management

Track all daily sales transactions. Filter, search, and export invoices for accounting or review.

![image2](image2)

---

### 3. Customer Management

View, add, edit, or delete customer records. Search and filter for efficient customer service.

![image3](image3)

---

### 4. Shift Management

Monitor shift-wise open/close balances, profits, and responsible staff for transparent operations.

![image4](image4)

You can also export detailed shift data to Excel for audit and analysis:

![image5](image5)

---

### 5. Product Management

Organize products by category, price, discount, stock, and images. Add, edit, or remove products easily.

![image6](image6)

---

### 6. Sales Report

Summarize sales by user, monitor performance, and export sales reports as PDF for business review.

![image7](image7)

---

### 7. Role Management

Assign roles and permissions to users (e.g., HR, Manager, Cashier, Accounting) for secure, organized access control.

![image8](image8)

Set roles and define what actions each user can perform, ensuring system security and efficient workflow.

![image9](image9)

---

## Tech Stack

- **Frontend:** React.js (JavaScript, HTML, CSS)
- **Backend:** Laravel (PHP)
- **Database:** MySQL
- **Other:** Axios, Bootstrap/Material UI

---

## Getting Started

### Prerequisites

- Node.js and npm
- Composer and PHP
- MySQL

### Backend Setup (Laravel)

```bash
git clone https://github.com/yourusername/coffeenisit-backend.git
cd coffeenisit-backend
composer install
cp .env.example .env
# Edit .env for your database credentials
php artisan key:generate
php artisan migrate
php artisan serve
```

### Frontend Setup (React)

```bash
git clone https://github.com/yourusername/coffeenisit-frontend.git
cd coffeenisit-frontend
npm install
npm start
```

Visit [http://localhost:3000](http://localhost:3000) to start using the POS system.

---

## Contact

Created by [Your Name]  
Email: [your.email@example.com]

---

> This project demonstrates skills in full-stack web development, UI/UX, and business software design. Thank you for considering my application for your internship program!
