# 🧾 Financepeer Assignment – Full Stack Application  
A complete **Flask + MySQL** web application implementing **user authentication**, **file upload**, and **JSON data visualization**.

---

## 📌 Features
### 🔐 1. User Authentication
- Secure **Sign Up**
- Login & Session handling
- MySQL-backed user storage

### 📤 2. JSON Upload Module
- Upload any JSON file  
- Automatically parses and stores into database

### 📊 3. JSON Data Viewer
- Displays uploaded JSON in a clean **Bootstrap table**
- Handles large datasets

---

## 🏗️ Tech Stack
| Layer | Technology |
|-------|------------|
| Backend | **Flask (Python)** |
| Database | **MySQL** |
| Frontend | **HTML + CSS + Bootstrap** |

---

## 📁 Project Structure
FPAssignment/
│── templates/
│ ├── index.html
│ ├── signup.html
│ ├── login.html
│ ├── fileload.html
│ ├── jsondata.html
│ └── result.html
│── server.py
│── financepeer.sql
│── data.json
│── README.md

---

---

## ▶️ Demo Video  
📌 **Full walkthrough:**  
https://drive.google.com/file/d/1WWUYoTxkEPD9DKA5-SMDEgZTSII74wM9/view

---

## 🖼️ Screenshots

### 🔹 Full JSON Data  
![](https://github.com/Kartikay77/FPAssignment/blob/main/full_json_data.png?raw=true)

### 🔹 Homepage  
![](https://github.com/Kartikay77/FPAssignment/blob/main/index.png?raw=true)

### 🔹 JSON Table  
![](https://github.com/Kartikay77/FPAssignment/blob/main/josn_data.png?raw=true)

### 🔹 Signup Page  
![](https://github.com/Kartikay77/FPAssignment/blob/main/signuppage.png?raw=true)

### 🔹 Signup Form  
![](https://github.com/Kartikay77/FPAssignment/blob/main/signup.png?raw=true)

---

## 🛠️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Kartikay77/FPAssignment
cd FPAssignment
```
### 2. Create a Virtual Environment
python3 -m venv venv
source venv/bin/activate      # Mac/Linux
venv\\Scripts\\activate       # Windows

### 3. Install Dependencies
pip install flask flask-mysql

### 4. Setup MySQL
mysql -u root -p
CREATE DATABASE financepeer;
USE financepeer;
SOURCE financepeer.sql;

### 5. Run the App
python3 server.py

---
# 👨‍💻 Author
Kartikay Gupta
B.Tech CSE – VIT Vellore (Reg No: 18BCE2199)
---

# ⭐ Support
If this project helped you, please ⭐ the repository!
