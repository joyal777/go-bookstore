# 📚 Go-Bookstore API

A robust RESTful API built with **Golang** using the **GORM** ORM and **MySQL** database. This project follows a clean MVC-inspired architecture to manage a bookstore inventory.

---

## 🚀 Features
* **CRUD Operations**: Create, Read, Update, and Delete books.
* **ORM Integration**: Uses GORM for seamless MySQL interactions.
* **Routing**: Powered by `gorilla/mux`.
* **Database Automigration**: Automatically creates tables on startup.

---

## 🛠️ Tech Stack
* **Language**: Go (Golang)
* **Database**: MySQL (via XAMPP/Local Server)
* **Frameworks**: 
    * `github.com/jinzhu/gorm`
    * `github.com/gorilla/mux`

---

## 📋 Prerequisites
Before running this project, ensure you have:
1. **Go** installed (1.18+)
2. **XAMPP** or MySQL Server running.
3. A database named `simple_bookstore` created in MySQL.

---

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone [https://github.com/joyal777/go-bookstore.git](https://github.com/joyal777/go-bookstore.git)
   cd go-bookstore

2. **Configure Database Connection**
   Open pkg/config/app.go and update your MySQL credentials:
   ```bash
   // Format: "username:password@/dbname?charset=utf8&parseTime=True&loc=Local"
   d, err := gorm.Open("mysql", "joyalxyz:joyaltonyxyz@/simple_bookstore?charset=utf8&parseTime=True&loc=Local")

3. **Install Dependencies**
   ```bash
   go mod tidy

4. **Run the Application**
   ```bash
   go run cmd/main/main.go
   
