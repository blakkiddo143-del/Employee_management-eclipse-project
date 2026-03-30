# Employee Management System (Spring Core Project)

## 📌 Project Overview

The **Employee Management System** is a simple Java application built using **Spring Core (Annotation Configuration)**.
It demonstrates basic **dependency injection, layered architecture, and CRUD-style operations** for managing employees.

This project is designed for learning **Spring Framework fundamentals** such as:

* IoC (Inversion of Control)
* Dependency Injection
* Java-based Configuration
* Layered architecture (Model, Repository, Service)

---

## 🛠 Technologies Used

* Java
* Spring Core
* Maven
* Eclipse IDE
* Annotation-based Configuration

---

## 📂 Project Structure

```
employee-management-eclipse-project
│
├── src/main/java/com/example/employee
│   │
│   ├── config
│   │   └── AppConfig.java
│   │
│   ├── main
│   │   └── EmployeeApp.java
│   │
│   ├── model
│   │   └── Employee.java
│   │
│   ├── repository
│   │   └── EmployeeRepository.java
│   │
│   └── service
│       └── EmployeeService.java
│
├── pom.xml
└── README.md
```

---

## ⚙️ Features

* Add new employees
* Store employee information
* Fetch all employees
* Layered architecture implementation
* Spring Dependency Injection

---

## 🧩 Components Explanation

### 1️⃣ Model

**Employee.java**

Represents the employee entity with fields such as:

* Employee ID
* Name
* Department

---

### 2️⃣ Repository Layer

**EmployeeRepository.java**

Handles employee data storage and retrieval.

---

### 3️⃣ Service Layer

**EmployeeService.java**

Contains business logic and interacts with the repository layer.

---

### 4️⃣ Configuration

**AppConfig.java**

Java-based configuration class used to configure Spring Beans.

---

### 5️⃣ Main Application

**EmployeeApp.java**

Entry point of the application.

Example logic:

```
service.createEmployee(101, "ABC", "IT");
service.createEmployee(102, "XYZ", "HR");

service.fetchAllEmployees().forEach(System.out::println);
```

---

## ▶️ How to Run the Project

### Step 1: Import Project

1. Open **Eclipse**
2. Click **File → Import**
3. Select **Existing Maven Project**
4. Choose the project folder

---

### Step 2: Build Project

Right click project → **Maven → Update Project**

---

### Step 3: Run Application

Navigate to:

```
EmployeeApp.java
```

Right click → **Run As → Java Application**

---

## 📊 Sample Output

```
Employee{id=101, name='ABC', department='IT'}
Employee{id=102, name='XYZ', department='HR'}
```

---

## 🎯 Learning Objectives

This project helps understand:

* Spring IoC Container
* BeanFactory
* AnnotationConfigApplicationContext
* Layered project structure
* Basic Spring project setup

---

## 👨‍💻 Author

**S ANBU SELVAN**
B.Tech Computer Science Engineering
Expected Graduation: 2027

---

## 📜 License

This project is for **educational purposes**.
