# 🎯 JavaFX Desktop CRUD Application

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
[MIT License](https://github.com/PeeterDalVitt/workshop-javafx-jdbc/blob/master/LICENSE)

A desktop application developed in Java and JavaFX, focusing on CRUD (Create, Read, Update, Delete) operations for managing departments and sellers. This project was built to explore real-world concepts like MVC design, FXML-based UIs, and database integration using **MySQL** and **MongoDB**.

---

## ⚙️ Features

- Clean GUI built with **FXML**
- Add, edit, and delete operations for Departments and Sellers
- Dynamic form validation with user-friendly error messages
- Database integration with **MySQL** (also tested with MongoDB)
- Modular MVC structure for scalability and clarity
- Interactive table views and responsive forms
- Uses custom utility classes for input constraints, alerts, and navigation

---

## 🧠 Tech Stack & Concepts

- **Java 21 (built with JDK 24)**
- **JavaFX SDK** for UI (FXML, SceneBuilder)
- **MySQL / MongoDB** for backend storage
- **OOP principles**: encapsulation, modularity, clean separation of concerns
- **Exception Handling** via custom exceptions
- **FXML Controllers**, GUI binding, and input parsing

---

## 🚀 How to Run

### ✅ Prerequisites

- Java JDK 21+ (project built using JDK 24)
- JavaFX SDK (properly installed and referenced)
- A MySQL (or MongoDB) instance running locally or remotely
- Update the `db.properties` file with your database credentials

### 🖥️ Run from command line

```bash
java --module-path D:\Coding\Distribution\javafx-sdk\lib --add-modules javafx.controls,javafx.fxml -cp workshop-javafx-jdbc.jar application.Main
```
And voilà! If you prefer (and uses Windows), you can save the code above in a .bat file that works as an icon to run the program directly without any terminals.

### 🙏 Screenshots

The overview of how the properties of the .bat file look like (look how the whole code is in the "path" section):
![image](https://github.com/user-attachments/assets/47d3e5f4-da4d-4612-9a8f-0b61f88e741d)
![image](https://github.com/user-attachments/assets/b006843a-0640-4dfd-ad98-94a5abc1b5d1)
![image](https://github.com/user-attachments/assets/4c99ce34-18a4-47dc-bd96-574aafe14b1f)


