# Coffee NISIT

Coffee NISIT is a modern web application designed to streamline coffee shop operations through an advanced point of sale (POS) system. Built with a React.js frontend and Laravel API backend, this project demonstrates my full-stack development skills, API integration, and a focus on user-centered design.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Authentication Forms](#authentication-forms)
  - [Login Form](#login-form)
  - [Create Account Form](#create-account-form)
- [Dashboard](#dashboard)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

- User authentication and secure session management
- Role-based access for administrators, employees, and customers
- Real-time sales analytics and performance dashboard
- Online order placement and management
- Inventory and product management
- Employee and shift management
- Detailed business reporting
- Responsive design for desktop and mobile devices

---

## Tech Stack

- **Frontend:** React.js, JavaScript, HTML, CSS
- **Backend:** Laravel (PHP), RESTful API
- **Database:** MySQL
- **UI Framework:** Bootstrap or Material-UI (optional)
- **Other:** Axios (API calls)

---

## Authentication Forms

Coffee NISIT provides a secure and user-friendly authentication system, including both login and account creation. These forms are designed for convenience, accessibility, and strong security, ensuring a smooth onboarding experience.

### Login Form

![image](https://github.com/user-attachments/assets/cd29c94a-537d-479c-8a2a-7b8ba1fbd5f6)

- **Modern UI:** Clean, branded design with intuitive layout.
- **Secure Authentication:** Email and password login, with masked input.
- **Session Management:** "Remember me for 30 days" for convenience.
- **Account Recovery:** "Forgot Password?" for easy password reset.
- **Account Creation Redirect:** Link for new users to create accounts.
- **Professional Context:** Real-world POS system image for context.

### Create Account Form

![image](https://github.com/user-attachments/assets/b1cab16c-a50e-4a76-852f-2af32c2013b8)

- **Simple Registration:** Sign up with full name, email, and password.
- **Password Strength Indicator:** Real-time feedback and checklist (min length, uppercase, lowercase, number, special character).
- **User Guidance:** Visual cues and validation.
- **Branded Experience:** Consistent, professional design.
- **Login Redirect:** Easy access for returning users.

Both forms are built for robust security and excellent user experience, reflecting industry standards and best practices.

---

## Dashboard

The core of Coffee NISIT is its analytics-rich admin dashboard, providing real-time insights into sales, orders, customers, and products.

![image](https://github.com/user-attachments/assets/e5efeae4-a863-4c3c-9908-2f70ea7fda8c)

**Dashboard Highlights:**
- Total sales tracking with visual analytics
- Overview of total orders, customers, and products
- Monthly sales comparison chart
- Quick navigation to sales, transactions, customers, orders, shifts, products, categories, employees, reports, and settings
- Responsive, user-friendly interface

This dashboard streamlines management operations and delivers actionable business intelligence at a glance.

---

## Installation

### Prerequisites

- Node.js & npm
- Composer & PHP
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

1. Start the Laravel backend server:  
   `php artisan serve`
2. Start the React frontend:  
   `npm start`
3. Visit `http://localhost:3000` in your browser.
4. Register or log in to begin managing coffee shop operations!

---

## Contributing

Contributions are welcome!  
To contribute:
1. Fork this repository
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Contact

Created by [Your Name]  
Contact: [your.email@example.com]

---

> **This project was built as part of my portfolio for internship applications. It demonstrates my abilities in both frontend and backend development, API integration, secure authentication, and responsive user interface design.**
