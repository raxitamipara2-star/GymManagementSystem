Nice 🔥
Here is a **professional README.md** you can directly paste into GitHub.

---

## 📌 **Gym Management System**

A complete **Gym Management System Web Application** built using **Firebase** and **JavaScript**.
This system helps gym owners manage members, payments, admins, and reports through a simple web interface.

---

## 🚀 **Live Website**

🔗 [https://gym-management-system-5829d.web.app](https://gym-management-system-5829d.web.app)

---

## 🛠 **Technologies Used**

* HTML
* CSS
* JavaScript
* Firebase Authentication
* Firebase Firestore
* Firebase Hosting

---

## 🔐 **User Roles**

The system supports two roles:

| Role   | Access                                    |
| ------ | ----------------------------------------- |
| Admin  | Full control (members, payments, reports) |
| Member | Personal dashboard and data               |

---

## 📂 **Features**

### 👨‍💼 Admin Panel

* View all members
* Add & delete members
* Record payments
* View payment reports
* Manage user roles

### 👤 Member Panel

* Register new account
* Login securely
* View personal dashboard
* View payment details

---

## 🔑 **Authentication**

Firebase Authentication is used for:

* Admin login
* Member login
* Signup system

Each user is assigned a role (`admin` or `member`) inside Firestore.

---

## 🗃 **Database Structure (Firestore)**

### **users**

```
users
 └── uid
      ├── name
      ├── email
      └── role (admin / member)
```

### **payments**

```
payments
 └── autoId
      ├── email
      ├── amount
      └── date
```

---

## 📁 **Project Structure**

```
GymManagementSystem
│
├── frontend
│   ├── index.html
│   ├── admin-login.html
│   ├── member-login.html
│   ├── signup.html
│   ├── member-dashboard.html
│   ├── payments.html
│   ├── reports.html
│   └── members.html
│
├── firebase.json
├── firestore.rules
└── README.md
```

---

## ⚙ **How to Run Locally**

1. Clone the repo:

```
git clone https://github.com/raxitamipara2-star/GymManagementSystem
```

2. Open the project folder
3. Open any `.html` file in browser
4. Firebase is already connected

---

## 📦 **Deployment**

This project is deployed using **Firebase Hosting** and connected to GitHub for automatic deployment.

---

## 👨‍💻 **Developer**

**Raxit Amipara**
Gym Management System Project

---
