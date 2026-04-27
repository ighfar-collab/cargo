# 🚚 Cargo Monitoring System

A web-based cargo monitoring system to track shipment status, manage logistics data, and improve operational efficiency.

## ✨ Features

- 📦 Real-time shipment tracking
- 🧾 Manage shipment data (CRUD)
- 📊 Dashboard monitoring
- 🔍 Search & filter shipments
- 🔐 Authentication system

## 🛠️ Tech Stack

- **Backend:** Laravel
- **Database:** MySQL
- **Frontend:** Bootstrap / Tailwind
- **JavaScript:** AJAX

## 📸 Screenshots

(https://ighfarhost.com/project-pos.html)

## 🎯 Purpose

This project is built to help logistics businesses:

- Monitor cargo delivery in real-time
- Reduce manual tracking errors
- Improve efficiency in shipment management
- Provide better transparency

## ⚙️ Installation

git clone https://github.com/ighfar-collab/cargo.git
cd cargo
composer install
cp .env.example .env
php artisan key:generate

### Setup Database

php artisan migrate
php artisan db:seed

### Run Project

php artisan serve

## 🔄 System Flow

1. User login
2. Admin creates shipment
3. Driver updates delivery status
4. System updates tracking in real-time
5. Dashboard reflects latest data

## 🔐 Link Demo (Optional)

https://cargo.ighfarhost.com

## 🔐 Demo Account (Optional)

- Super-admin
  Email: [superadmin@mail.com]
  Password: password123

- Admin
  Email: [admin@mail.com]
  Password: password

- Mitra
  Email: [mitra@mail.com]
  Password: password

- driver
  Email: [drivv@mail.com]
  Password: password

## 🚀 Future Development

- API integration (JNE, J&T, etc.)
- Notification system (Email / WhatsApp)
- Export PDF / Excel
- Advanced role management

## 👨‍💻 Author

**Ighfar Ilaina**
Backend Developer (Laravel)
🔗 https://github.com/ighfar-collab

## 💡 Project Value

This project simulates a real-world logistics system used in production environments, focusing on:

- Scalable backend architecture
- Efficient shipment tracking workflow
- Role-based system for multi-user operations
- Real-time data handling for logistics monitoring
