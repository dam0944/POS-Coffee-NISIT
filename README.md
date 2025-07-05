# Coffee NISIT POS System

Coffee NISIT is a modern Point of Sale (POS) web application designed for coffee shops, built with a focus on ease of use, powerful features, and clean design. This system streamlines daily operations—sales, inventory, customers, employees, and reporting—making it ideal for both staff and managers.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Screenshots](#screenshots)
  - [POS Screen](#pos-screen)
  - [Invoice Management](#invoice-management)
  - [Customer Management](#customer-management)
  - [Shift Management](#shift-management)
  - [Excel Export](#excel-export)
  - [Product Management](#product-management)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contact](#contact)

---

## Overview

Coffee NISIT helps coffee shop owners and staff manage sales, customers, products, employees, and finances in one simple, intuitive platform. It supports daily reporting, sales analysis, and operational transparency—empowering better business decisions.

---

## Features

- Fast, intuitive POS for order taking and payment
- Real-time sales and invoice tracking
- Shift-based sales/profit summaries
- Powerful customer management
- Product and inventory management
- Export reports/data to Excel
- User-friendly interface and responsive design

---

## Screenshots

### POS Screen

Effortless order taking with visual product catalog, real-time cart, and quick payment actions.

![image1](image1)

---

### Invoice Management

Track all daily sales transactions, filter by user/date, and export invoices for reporting.

![image2](image2)

---

### Customer Management

View, add, edit, and delete customer records. Search and filter with ease.

![image3](image3)

---

### Shift Management

Monitor each shift’s open/close balances, profits, times, and responsible users for full financial transparency.

![image4](image4)

---

### Excel Export

Export shift, sales, and other operational data to Excel for audits, analysis, or sharing with accounting.

![image5](image5)

---

### Product Management

Organize all products with category, price, discount, stock, and images. Add, edit, or remove products easily.

![image6](image6)

---

## Tech Stack

- **Frontend:** React.js, JavaScript, HTML, CSS
- **Backend:** Laravel (PHP), REST API
- **Database:** MySQL
- **Other:** Axios, Bootstrap/Material-UI (optional)

---

## Getting Started

### Prerequisites

- Node.js and npm
- Composer and PHP
- MySQL

### Backend (Laravel)

```bash
git clone https://github.com/yourusername/coffeenisit-backend.git
cd coffeenisit-backend
composer install
cp .env.example .env
# Configure database settings in .env
php artisan key:generate
php artisan migrate
php artisan serve
```

### Frontend (React)

```bash
git clone https://github.com/yourusername/coffeenisit-frontend.git
cd coffeenisit-frontend
npm install
npm start
```

---

## Usage

1. Ensure your Laravel backend is running (`php artisan serve`).
2. Start the React frontend (`npm start`).
3. Open your browser to [http://localhost:3000](http://localhost:3000).
4. Register a user account or log in to start using the POS system.

---

## Contact

Created by [Your Name]  
Email: [your.email@example.com]

---

> This project demonstrates my skills in full-stack web development, UI/UX, and business software—thank you for your consideration for internship opportunities!
