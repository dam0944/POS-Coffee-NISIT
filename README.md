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

![image](https://github.com/user-attachments/assets/a65db1a9-ab97-4b50-bd24-e18cb9e1895a)

---

### 2. Invoice Management

Track all daily sales transactions. Filter, search, and export invoices for accounting or review.

![image](https://github.com/user-attachments/assets/92e9df4c-1200-4cab-9d01-bd504ceff247)

---

### 3. Customer Management

View, add, edit, or delete customer records. Search and filter for efficient customer service.

![image](https://github.com/user-attachments/assets/5da299b9-4aa2-4056-b772-7935de9e30b0)

---

### 4. Shift Management

Monitor shift-wise open/close balances, profits, and responsible staff for transparent operations.

![image](https://github.com/user-attachments/assets/4a79eecc-b934-44a1-ba59-90c68b9a0c9c)

You can also export detailed shift data to Excel for audit and analysis:

![image](https://github.com/user-attachments/assets/097908a0-ac38-470b-8071-81775b5b3b71)

---

### 5. Product Management

Organize products by category, price, discount, stock, and images. Add, edit, or remove products easily.

![image6](image6)

---

### 6. Sales Report

Summarize sales by user, monitor performance, and export sales reports as PDF for business review.

![image](https://github.com/user-attachments/assets/c886d2f3-4b12-42a8-9ecb-0522e351cd49)

---

### 7. Role Management

Assign roles and permissions to users (e.g., HR, Manager, Cashier, Accounting) for secure, organized access control.

![image](https://github.com/user-attachments/assets/a08c1758-af9b-4c52-8639-13fd1a617dbd)

Set roles and define what actions each user can perform, ensuring system security and efficient workflow.

![image](https://github.com/user-attachments/assets/5044c446-d05c-490f-8efe-b54d9f576e8c)

---

## Tech Stack

- **Frontend:** React.js (JavaScript, HTML, CSS)
- **Backend:** Laravel (PHP)
- **Database:** MySQL
- **Other:** Axios, TailwindCSS/Ant Design

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

Created by [Ang Dam]  
Email: [dam619404@gmail.com]

---

> This project demonstrates skills in full-stack web development, UI/UX, and business software design. Thank you for considering my application for your internship program!
