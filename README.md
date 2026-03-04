# 🧵 Tailor Notebook

Tailor Notebook is a web-based management system designed for tailoring shops to manage customers, appointments, employees, and inventory in a digital way. It helps tailors keep track of measurements, orders, and customer information efficiently instead of maintaining manual records.

---

## 🚀 Features

- Customer management
- Appointment scheduling
- Employee management
- Inventory tracking
- Simple dashboard for tailoring operations
- File uploads for storing data
- Organized database structure

---

## 🛠 Tech Stack

**Backend**
- Node.js
- Express.js

**Frontend**
- EJS Templates
- HTML
- CSS
- JavaScript

**Database**
- MongoDB
- Mongoose ODM

---

## 📂 Project Structure
TailorNotebook
│
├── models
│   ├── Appointment.js
│   ├── customer.js
│   ├── Employee.js
│   ├── Inventory.js
│   └── user.js
│
├── public
│   ├── uploads
│   ├── script.js
│   └── style.css
│
├── views
│
├── .env.example
├── app.js
├── create-sample-customers.js
├── seed.js
├── package.json
└── README.md

---

## ⚙️ Installation

### 1 Clone the repository
git clone https://github.com/OjeswariDevi/TailorNotebook.git

### 2 Navigate to project folder
cd TailorNotebook


### 3 Install dependencies


npm install


### 4 Setup environment variables

Create a `.env` file based on `.env.example`

Example:


MONGO_URI=your_mongodb_connection_string
PORT=3000


### 5 Run the application


npm start


or


node app.js


Open the browser:


http://localhost:3000


---

## 📊 Database Models

The system includes the following models:

- **Customer** – stores customer details
- **Appointment** – manages tailoring appointments
- **Employee** – tracks employees
- **Inventory** – manages materials and stock
- **User** – authentication and system access

---

## 📈 Future Improvements

- Online appointment booking
- Measurement tracking
- PDF invoice generation
- Admin dashboard
- Cloud deployment
- Mobile responsive UI

---

## 👩‍💻 Author

**Ojeswari Devi**  
B.Tech Computer Science Engineering  
Full Stack Web Developer  

GitHub: https://github.com/OjeswariDevi
