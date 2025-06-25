# 🌐💻  NetZone-CyberCafe- Django Web Application

---

## 🚀 Project Overview

This project designs a computer system for a **Cyber Café** to simplify management of user details, internet usage, and billing.  
The system maintains records of users, cabins, and login history, providing both **prepaid** and **postpaid** account options for Account Users and Walk-in Users respectively.

The software is powered by **Python** and **Django**, ensuring reliable and efficient service.  
The database used is **SQLite**, providing portability and easy management.

---

## 🛠️ Technologies Used

| Component          | Details                                  |
|--------------------|------------------------------------------|
| 🐍 Language        | Python                                   |
| 🌐 Framework       | Django                                   |
| 🗄️ Database       | SQLite                                   |
| 🎨 UI              | HTML, AJAX, jQuery, JavaScript           |
| 🧠 IDE             | PyCharm                                  |
| 🌍 Browser Support | Mozilla, Google Chrome, IE8, Opera       |

---

## 📦 Project Modules

### 🔐 Admin Module
- **Dashboard:** View total computers and total users.
- **Computer Management:** Add, update, and delete computers.
- **User Management:** Add new users, update out time, price, remarks; view old users’ details.
- **Search Users:** Search users by entry ID.
- **Report:** View user statistics for selected periods.
- **Profile:** Update admin profile.
- **Change Password:** Admin can change password.
- **Password Recovery:** Admin can recover password if forgotten.
- **Logout:** Secure logout functionality.

---

## 🖼️ Screenshots

*(Upload screenshots to your repo and update links below)*

| Dashboard          | Computer Management      | User Management        |
|--------------------|-------------------------|-----------------------|
| ![Dashboard](link) | ![Computers](link)      | ![Users](link)        |

| Reports            | Profile Update          | Login Screen           |
|--------------------|-------------------------|-----------------------|
| ![Reports](link)   | ![Profile](link)        | ![Login](link)        |

---

## ▶️ How to Run the Project

```bash
# 1. Clone the repository
git clone https://github.com/madhavidurga2000/CyberCafeSystem-Django.git
cd CyberCafeSystem-Django/cybercafe/ccms

# 2. Create and activate virtual environment
python -m venv venv

# For Windows:
venv\Scripts\activate

# For Linux/macOS:
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Apply database migrations
python manage.py migrate

# 5. Run the Django development server
python manage.py runserver

# 6. Open your browser and go to:
# http://127.0.0.1:8000
##🔑 Default Admin Login (Example)
Role	Username	Password
Admin	admin@cyber.com	Test@123

(Replace with your actual login credentials)


## 📹 Demo Video  
▶️ [Click here to download and watch the demo video](https://raw.githubusercontent.com/madhavidurga2000/NetZone-CyberCafe-webapp/master/demo1.mp4)

##👩‍💻 Author
Madhavi Durga
Email: madhavidurga2000@gmail.com
GitHub: @madhavidurga2000

#📄 License
This project is for educational use. Feel free to use or improve it with credit.






