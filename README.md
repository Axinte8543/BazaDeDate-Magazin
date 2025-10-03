# 🛒 Store Database (BazaDeDate-Magazin)

## 📖 Description
This project is a **relational database** designed to support a store system.  
It stores information about clients, products, employees, and orders.  
The database also tracks product details (albums, books, films), purchase history, and store performance.

## 🗂️ Entities
- **Client** – stores customer information (name, surname, phone number, personal details).
- **Order** – contains the client ID, delivery date, and arrival date. Linked with products.
- **Product** – represents items sold in the store (with sub-entities: **Music Album, Book, Film**). Includes details such as price, genre, and creator.
- **Store** – connected with products and employees.
- **Employee** – stores employee data (email, city, unique details).
- **Job** – describes the employee’s position and working hours.

## ⚙️ Features
- Record purchased products, quantity, price, order date, and payment method.
- Manage and analyze store performance.
- Store customer history for better customer relationship management (CRM).
- Manage inventory with details such as type, release year, creator, and genre.

## 🛠️ Technologies Used
- **SQL / Relational Databases** (design, ER modeling).
- Documentation in PDF: `243_Avrinte_TeodorStefan_ProiectSGBD.pdf`.

## 🚀 Usage
The database can be used to:
- Track and analyze customer purchases.
- Manage product categories and stock.
- Organize store employees and job roles.

## 👤 Author
Project created by **Axinte**.
