# 🚀 Task Manager Application  

## **📌 Overview**
This is a **Task Manager Web Application** built with **.NET MVC**, **Bootstrap**, **HTML, CSS, JavaScript**, and **SQL Server**.  
It allows **Admins** to create, edit, and delete tasks, while **Users** can create and edit their own tasks.  
Each user session is managed securely.  

---

## **🛠 Tech Stack**
- **Backend:** ASP.NET MVC (C#)
- **Frontend:** Bootstrap, HTML, CSS, JavaScript  
- **Database:** SQL Server with Entity Framework Core  
- **Authentication:** Session-based login  
- **Version Control:** Git & GitHub  

---

## **✅ Features & Descriptions**
### **1️⃣ User Authentication (Sign Up & Log In)**
🔹 Users can **register** and **log in** securely.  
🔹 Sessions are created for each user after login.  
🔹 Ensures **only authenticated users** can access the system.  
🔹 Admins have extra privileges to manage all tasks.  

### **2️⃣ CRUD Operations (Create, Read, Update, Delete)**
🔹 Users can **create tasks** with a title, description, category, priority, and due date.  
🔹 Tasks can be **viewed in a list format** for easy management.  
🔹 Tasks can be **updated** to change details like priority or description.  
🔹 Users can **delete** tasks when they are no longer needed.  

### **3️⃣ Task Categories & Tags**
🔹 Users can categorize tasks (e.g., **Work, Personal, Urgent, Shopping**).  
🔹 Multiple **tags** can be added to help with filtering.  

### **4️⃣ Task Status Management**
🔹 Users can **mark tasks as Completed or Pending**.  
🔹 Completed tasks can be easily identified.  
🔹 Helps in tracking work progress.  

### **5️⃣ Search & Filter Tasks**
🔹 Users can **search tasks by title**.  
🔹 Tasks can be **filtered by category** or **status (Pending/Completed)**.  
🔹 Helps users find tasks quickly.  

### **6️⃣ Bootstrap UI & Responsive Design**
🔹 Modern and **responsive UI** using Bootstrap.  
🔹 Works on **desktop, tablet, and mobile** devices.  

### **7️⃣ Admin & User Roles**
🔹 **Admins** can manage all users' tasks.  
🔹 **Users** can only manage their own tasks.  

### **8️⃣ Secure Session Management**
🔹 **User sessions** are created after login to prevent unauthorized access.  
🔹 Sessions expire after logout or inactivity.  

---

## **📌 GitHub Setup**
### **1️⃣ Initialize Git in Your Project**
```sh
git init
git add .
git commit -m "Initial commit - Task Manager Application"
