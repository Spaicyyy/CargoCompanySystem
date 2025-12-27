# 🚚 Cargo Automation System (OOP Project)

A Java-based logistics management system designed to simulate real-world cargo operations, vehicle management, and financial transactions.

## 🌟 Features
* **Object-Oriented Design:** Utilizes Polymorphism, Inheritance, and Encapsulation.
* **Dynamic Pricing:** Calculates costs based on distance (coordinates), weight, and shipping type (Standard, Express, Cold Chain).
* **Vehicle Management:** Automatically assigns suitable vehicles (Truck, Drone, Motorcycle) based on cargo weight.
* **Financial System:** Integrated bank account simulation with deposit, refund, and payment authorization logic.
* **Validation:** Custom exception handling (`WrongDataPass`) to ensure data integrity.

## 🛠️ Tech Stack
* **Language:** Java (JDK 17+)
* **Concepts:** OOP, Collections, Exception Handling
* **Architecture:** Separation of Concerns (AppData, MenuController, AdminPanel)

## 🚀 How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/Spaicyyy/Cargo-Automation-System.git](https://github.com/Spaicyyy/Cargo-Automation-System.git)
    ```
2.  Open the project in IntelliJ IDEA.
3.  Run `Main.java`.
4.  **Login Credentials:**
    * Username: `Avaz`
    * Password: `123`

## 📂 Project Structure
* `src/Main.java`: Entry point.
* `src/MenuController.java`: Handles user interaction and logic.
* `src/AdminPanel.java`: Initializes dummy data (Cities, Vehicles).
* `src/Vehicle.java`: Abstract base class for all transport types.

## 📝 License
This project was developed for educational purposes at Karadeniz Technical University.
