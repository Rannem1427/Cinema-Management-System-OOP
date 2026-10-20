# 🎬 Cinema Management System (OOP Project)

A comprehensive **Cinema Management System** built using **Java** and core **Object-Oriented Programming (OOP)** principles. This application handles essential cinema operations including employee management, movie and hall scheduling, seat booking with 2D arrays, food inventory, and transaction handling with file I/O.

---

## 👥 Contributors & Team Members

Developed by Computer Science students at **Umm Al-Qura University**:

- **Raneem Majed Al-Moabadi** (Movie & Hall Systems, Report Introduction)
- **Jood Omar Banjar** (Employee System & UML Diagram Design)
- **Manaya Hatim Shoaib** (Food, Customer, Booking, & Utility Systems)
- **Amal Maqram** (Cinema System Integration & Main Logic)

**Instructor:** Dr. Ibtihal Abdulmalik Qoqandi  
**Department:** Computer Science, Umm Al-Qura University

---

## 🚀 Key Features & System Modules

### 📽️ 1. Movie & Hall System
- **Movie Management:** Manage movie details including title, genre (`MovieGenre` Enum), duration, price, and description.
- **Hall & Seating Layout:** Represent cinema halls with both 1D arrays (row counts) and 2D arrays (interactive grid for seat booking and availability checking).

### 👨‍💼 2. Employee & Role Management
- Roles managed via the `Job` Enum (`MovieHallManager`, `FoodManager`).
- **`MovieHallManager`**: Handles adding, modifying, and removing movies and halls.
- **`FoodManager`**: Manages cinema food stock and inventory operations.

### 🎟️ 3. Customer & Booking System
- **Customer:** Encapsulated entity storing customer ID, name, and phone with strict data validation.
- **Booking:** Links movies, halls, seats, showtimes, and customers together with tax calculation via `Utility`.

### 🍿 4. Food & Utility Operations
- **Food Inventory:** Tracks stock levels with input validation and recursive stock calculation (`recursiveCount`).
- **Utility:** Static methods handling tax calculation (15% VAT) and persistent file logging (`FileWriter` & `BufferedReader`).

---

## 🛠️ Object-Oriented Programming (OOP) Concepts Applied

- **Encapsulation:** Private data fields across all domain models with public getters, setters, and strict validation checks.
- **Inheritance:** `MovieHallManager` and `FoodManager` classes extend the `Employee` base class.
- **Polymorphism / Method Overriding:** Customized `toString()` methods across all entities.
- **Aggregation & Composition:** Complex domain models (`Booking` composes `Movie`, `Hall`, and `Customer`).
- **Exception Handling:** Robust `try-catch` blocks and custom exception throwing for invalid inputs (e.g., negative IDs, null names, out-of-bound seat bookings).
- **Recursion:** Applied in stock tracking inside the `Food` class.

---

## 📐 System Architecture / UML Diagram

The overall system architecture and relationships between classes are modeled as follows:

- **Central Hub:** `CinemaSystem` acts as the main database maintaining lists (`ArrayList`) of movies, halls, customers, employees, bookings, and food items.
- **Entry Point:** `CinemaMain` simulates the end-to-end execution flow of the system.

*(You can insert your UML diagram image here)*

---

## 💻 How to Run the Project

1. Clone this repository:
   ```bash
   git clone [https://github.com/Rannem1427/Cinema-Management-System.git](https://github.com/Rannem1427/Cinema-Management-System.git)
# Cinema-Management-System-OOP
A comprehensive Cinema Managemen
