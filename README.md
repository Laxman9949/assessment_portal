# 📝 Assessment Portal – Flask Web Application

An online **Assessment Portal Web Application** developed using **Python Flask**, **MySQL**, **HTML**, **CSS**, and **JavaScript**.  
This system allows users to register, log in, and access assessments, while administrators can securely create and manage tasks.

---

## 🚀 Features

### 👤 User Module
- User registration (Sign Up)
- Secure login & logout
- Session-based authentication
- Access assigned tasks after login

### 🛠 Admin Module
- Separate admin login
- Create new assessment tasks
- Restricted access for admin pages
- Secure routing

### 💾 Database
- MySQL database integration
- User and admin credential storage
- Task data storage

### 🌐 Web Interface
- Responsive UI
- Clean HTML & CSS design
- Separate pages for login and signup
- Flash messages for alerts

---

## 🧰 Technologies Used

| Technology | Purpose |
|-----------|---------|
| Python | Backend logic |
| Flask | Web framework |
| MySQL | Database |
| HTML5 | Structure |
| CSS3 | Styling |
| JavaScript | Frontend interactions |
| Jinja2 | Template rendering |

---

## 📁 Project Structure

assessment-portal/
│
├── app.py
├── db_database.sql
├── static/
│ ├── style.css
│ └── images/
│
├── templates/
│ ├── login.html
│ ├── signup.html
│ ├── admin_login.html
│ ├── dashboard.html
│ ├── create_task.html
│ └── base.html
│
├── README.md
└── requirements.txt


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/assessment-portal.git
cd assessment-portal

2️⃣ Create Virtual Environment
python -m venv venv
venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

🗄 Database Setup

Open MySQL

Create a database:

CREATE DATABASE assessment_portal;


Import SQL file:

SOURCE db_database.sql;


Update database credentials in app.py:

host="localhost"
user="root"
password="your_password"
database="assessment_portal"

▶️ Run the Application
python app.py


Then open your browser:

http://127.0.0.1:5000/
