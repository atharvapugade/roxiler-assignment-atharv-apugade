# FullStack Intern Coding Challenge – Roxiler Systems
### Candidate: Atharv Apugade

---

## 📌 Project Overview
This project is built as part of the **Roxiler Systems Technical Assignment**.  
It is a **full-stack web application** developed using **React.js (frontend)**, **Express.js (backend)**, and **MySQL (database)**.  

The application allows users to submit ratings for registered stores on the platform.  
Based on their role (Admin, Normal User, Store Owner), they get different access and functionalities after logging in.

---

## 🚀 Tech Stack
- **Frontend:** React.js, HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MySQL (with Sequelize ORM)  
- **Other Tools/Libraries:** Axios, Chart.js (if used), Bootstrap/Material UI (if used)  

---

## 👥 User Roles & Functionalities

### 🔹 System Administrator
- Add new stores, normal users, and admin users.  
- Dashboard with stats:  
  - Total users  
  - Total stores  
  - Total ratings  
- View and filter lists of stores and users (by Name, Email, Address, Role).  
- View details of all users (Store Owner details include their rating).  
- Log out from the system.  

### 🔹 Normal User
- Sign up and log in (with validations).  
- Update password after logging in.  
- View all registered stores.  
- Search stores by **Name** or **Address**.  
- Store listings display:  
  - Store Name, Address, Overall Rating, User’s Rating.  
- Submit or update ratings (1–5) for stores.  
- Log out from the system.  

### 🔹 Store Owner
- Log in to the platform.  
- Update password after logging in.  
- Dashboard functionalities:  
  - View users who submitted ratings for their store.  
  - See their store’s average rating.  
- Log out from the system.  

---

## 🛡️ Form Validations
- **Name:** 20–60 characters  
- **Address:** Max 400 characters  
- **Password:** 8–16 characters, at least 1 uppercase + 1 special character  
- **Email:** Must follow standard email validation  

---

## 📂 Folder Structure
roxiler-assignment-atharv-apugade/
├── roxiler-frontend/ 
├── roxiler-backend/ 



---

## ⚙️ Setup Instructions

 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/roxiler-assignment-atharv.git
cd roxiler-assignment-atharv-apugade


 2. Backend setup
cd roxiler-backend
npm install

Configure Database
Create a MySQL database (e.g., roxiler_db).

Add .env file inside roxiler-backend/ with DB credentials:
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=roxiler_db
DB_DIALECT=mysql
PORT=5000
JWT_SECRET=your_jwt_secret

Run backend server:
npm start


3. Frontend Setup
cd roxiler-frontend
npm install
npm start


✨ Features Implemented
1.Role-based authentication (Admin, Normal User, Store Owner).
2.CRUD operations for users, stores, and ratings.
3.Store rating system (1–5).
4.Search, sort, and filter functionality.
5.Secure password handling and JWT authentication.
6.Responsive frontend with simple UI.



📸 Screenshots
roxiler-frontend/screenshots


Candidate Info:

Name: Atharv Apugade
Role Applied: Full Stack Developer Intern
Tech Stack: React.js, Express.js, MySQL
Location Preference: Pune
