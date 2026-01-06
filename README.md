# 📝 ToDo App – Spring Boot & Thymeleaf

A simple and efficient **ToDo Web Application** built using **Spring Boot**, **Thymeleaf**, and **Bootstrap**, designed to manage daily tasks effectively.

---

## 🚀 Features

- ➕ Add new tasks  
- ✏️ Update existing tasks  
- ❌ Delete tasks  
- ✅ Mark tasks as completed  
- 📋 View all tasks  
- 📱 Responsive UI using Bootstrap  

---

## 🛠️ Tech Stack

- **Backend:** Java, Spring Boot  
- **Frontend:** Thymeleaf, HTML, Bootstrap CSS  
- **Database:** MySQL  
- **Build Tool:** Maven  
- **IDE:** IntelliJ IDEA / Spring Tool Suite  

---

## 🧩 Architecture

- Follows **MVC (Model–View–Controller)** architecture  
- Uses **Spring Boot annotations** for dependency injection  
- Server-side rendering with **Thymeleaf templates**  

---

## 📂 Project Structure

TodoApp
│
├── src/main/java
│ └── com.example.todo
│ ├── controller
│ ├── model
│ ├── repository
│ └── service
│
├── src/main/resources
│ ├── templates
│ ├── static
│ └── application.properties
│
└── pom.xml


---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Saikrishna185/TodoApp.git
cd TodoApp

2️⃣ Configure MySQL Database

Update application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/todo_db
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update

3️⃣ Run the Application
mvn spring-boot:run

4️⃣ Open in Browser
http://localhost:8080/

🎯 Learning Outcomes

Practical experience with Spring Boot MVC

CRUD operations using Spring Data JPA

Thymeleaf template integration

Database connectivity with MySQL

Responsive UI design using Bootstrap

👨‍💻 Author

Sai Krishna Sahu

GitHub: https://github.com/Saikrishna185

LinkedIn: https://www.linkedin.com/in/sai-krishna-sahu-51a33526b/

📜 License

This project is licensed under the MIT License.
