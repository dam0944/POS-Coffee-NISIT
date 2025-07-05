# Coffee NISIT

Coffee NISIT is a modern web application designed to streamline coffee shop operations with an advanced Point of Sale (POS) system. Built using React.js for the frontend and Laravel for the backend, this project demonstrates my full-stack development skills, API integration, and focus on user-centered design.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
  - [Authentication Forms](#authentication-forms)
    - [Login Form](#login-form)
    - [Create Account Form](#create-account-form)
  - [Dashboard](#dashboard)
  - [Point of Sale (POS)](#point-of-sale-pos)
  - [Invoice Management](#invoice-management)
  - [Customer Management](#customer-management)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview

Coffee NISIT helps coffee shop owners efficiently manage sales, inventory, employees, and customer data—all from a single, intuitive platform. With powerful analytics and daily reporting, it empowers businesses to improve service and make data-driven decisions.

---

## Features

- Secure user authentication and session management
- Role-based access for administrators, staff, and customers
- Real-time sales analytics and reporting dashboard
- Modern Point of Sale (POS) with order/cart management
- Product and inventory management
- Employee and shift management
- Daily invoice management and transaction history
- Comprehensive customer management
- Exportable reports (Excel)
- Responsive design for desktop and mobile

---

## Tech Stack

- **Frontend:** React.js, JavaScript, HTML, CSS
- **Backend:** Laravel (PHP), RESTful API
- **Database:** MySQL
- **UI Framework:** Custom + Bootstrap/Material-UI (if used)
- **Other:** Axios (API calls)

---

## Screenshots

### Authentication Forms

#### Login Form

![image2](image2)

- Clean, modern interface with Coffee NISIT branding
- Secure authentication: Email & password login (masked input)
- "Remember me for 30 days" for convenience
- "Forgot Password?" link for easy password recovery
- Quick link to create a new account
- Real-world POS context image for professional touch

#### Create Account Form

![image3](image3)

- Simple registration: Full name, email, password fields
- Real-time password strength indicator and requirements checklist
- Visual cues and validation for user guidance
- Consistent, professional design
- Link to login for returning users

---

### Dashboard

![image1](image1)

- Analytics-rich admin dashboard with real-time business metrics
- Total sales, total orders, total customers, and total products at a glance
- Monthly sales comparison chart
- Quick links to Sales, Transactions, Customers, Orders, Shifts, Products, Categories, Employees, Reports, and Settings
- Clean, user-friendly layout

---

### Point of Sale (POS)

![image4](image4)

- Intuitive, visual menu with product images, categories, and prices
- Quick Add to Cart with support for discounts and promotions
- Real-time order/cart panel with subtotal and total calculation
- Staff can clear, print, or proceed to payment with one click
- Product availability and preparation time displayed for each item
- Fast product search and category filters
- Built for speed, accuracy, and a superior customer experience

---

### Invoice Management

![image5](image5)

- Daily sales overview: Total sales, total invoices, unique customers
- Detailed transaction records: Invoice ID, payment method, amount, quantity, date, time, seller, and status
- Powerful filters for user, date, and time
- Status tracking for each transaction (e.g., rejected, completed)
- Export invoices to Excel for reporting or analysis
- Create, edit, or delete invoices easily
- Essential for business audits and financial transparency

---

### Customer Management

![image6](image6)

- Organized customer list with name, gender, phone, email, address, and avatar
- Quick actions: Add, edit, or delete customer records
- Search and filter customers efficiently
- Gender and contact info highlighted for easy recognition
- Pagination for handling large customer databases
- Clean, modern interface for easy management

---

## Installation

### Prerequisites

- Node.js and npm
- Composer and PHP
- MySQL

### Backend (Laravel API)

```bash
git clone https://github.com/yourusername/coffeenisit-backend.git
cd coffeenisit-backend
composer install
cp .env.example .env
# Configure your database settings in .env
php artisan key:generate
php artisan migrate
php artisan serve
```

### Frontend (React.js)

```bash
git clone https://github.com/yourusername/coffeenisit-frontend.git
cd coffeenisit-frontend
npm install
npm start
```

---

## Usage

1. Make sure your backend (Laravel API) is running:  
   `php artisan serve`
2. Start the frontend (React):  
   `npm start`
3. Open your browser and go to `http://localhost:3000`
4. Register or log in to start using Coffee NISIT!

---

## Contributing

Contributions are welcome!

To contribute:
1. Fork this repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Contact

Created by [Ang Dam]  
Email: [dam619404@gmail.com]

---

> **This project was built as part of my portfolio to demonstrate my abilities in full-stack web development, UI/UX design, and real-world business application development. Thank you for reviewing my work for internship consideration!**
