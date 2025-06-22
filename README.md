
## 📚 Biblosphere – Marketplace for Book Sharing

**Biblosphere** is a web-based platform that allows users to buy, sell, and manage books. It includes features like user authentication, book listing management, a shopping cart, and secure payments via Razorpay.

---

### 🚀 Features

* User Registration & Login
* Add/Edit/Delete Books (Admin & User)
* Book Search & Filter Functionality
* Shopping Cart System
* Order Placement
* Razorpay Integration for Payments
* Admin Panel for Book Management

---

### 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript, Bootstrap
* **Backend:** Java, JSP, Servlets
* **Database:** MySQL
* **Server:** Apache Tomcat

---

### 🖥️ Project Screenshots

| Home Page                |   
| ------------------------ | 
| ![image](https://github.com/user-attachments/assets/404b12e4-f39f-46d4-ac4d-b4cab0372acf)
| ![image](https://github.com/user-attachments/assets/2c8f28b9-0067-4ddb-8054-8a3571917145)


|  Admin Panel              |  
| ------------------------- |
| ![image](https://github.com/user-attachments/assets/24d2f271-cbc5-4298-acfa-564c555333ce)

  
| Shopping Cart             |  
| ------------------------- |
| ![image](https://github.com/user-attachments/assets/023023c6-fb08-426c-a28f-de21be08f876)


---

### ⚙️ How to Run Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/itsaditya0108/Biblosphere.git
   ```

2. **Import the project into Eclipse/NetBeans/IntelliJ as a Java Web Project.**

3. **Set up the MySQL Database:**

   * Create a database named `biblosphere`
   * Import the `biblosphere.sql` file (provided in the repo)

4. **Configure `DBConnection.java` with your MySQL credentials**

5. **Run on Apache Tomcat:**

   * Deploy project to local Tomcat server (e.g., `http://localhost:8080/Biblosphere`)

---

### 📁 Folder Structure

```
Biblosphere/
├── src/
│   └── com.biblosphere (Java Classes: Servlets, DAO, Models)
├── WebContent/
│   ├── jsp/
│   ├── css/
│   ├── js/
│   └── index.jsp
├── WEB-INF/
│   └── web.xml
├── biblosphere.sql
└── README.md
```

---

### 📦 Future Improvements

* Email notifications on order
* Mobile responsiveness
* Review & Rating system
* Docker support

---

### 👨‍💻 Author

* **Aditya Verma**
  [GitHub](https://github.com/itsaditya0108) | [Portfolio](https://itsaditya0108.github.io/adityaportfolio) | [LinkedIn](https://linkedin.com/in/aditya-verma-86b726304)

---
