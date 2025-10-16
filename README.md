# 🧩 CRM Application

A **Customer Relationship Management (CRM)** web application built with **Django**, **Python**, and **MySQL**.  
This app allows users to **register, log in, log out**, and **manage customer records** with full **CRUD functionality** — all wrapped in a clean, responsive interface.

---

## 🚀 Features

✅ **User Authentication**
- Secure **Register**, **Login**, and **Logout** functionality.
- Passwords encrypted using Django’s built-in authentication system.

✅ **Customer Management**
- **Add**, **View**, **Update**, and **Delete** customer records.
- Organized dashboard displaying client information.

✅ **Database Integration**
- **MySQL** database to store user and customer data.
- Fully integrated with Django’s ORM for easy query management.

✅ **Responsive UI**
- Clean and minimal front-end built with Django templates and Bootstrap (or your styling framework if you used one).

---

## 🛠️ Tech Stack

| Technology | Description |
|-------------|-------------|
| **Python** | Core programming language |
| **Django** | Web framework handling backend logic and routing |
| **MySQL** | Relational database for storing records |
| **HTML / CSS / Bootstrap** | Front-end styling and layout |
| **SQLite** *(optional)* | Default Django database (used for testing) |

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/yourusername/your-repo-name.git

# 2️⃣ Navigate into the project directory
cd your-repo-name

# 3️⃣ Create and activate a virtual environment
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# 4️⃣ Install dependencies
pip install -r requirements.txt

# 5️⃣ Configure your MySQL database in settings.py
# Example:
# DATABASES = {
#     'default': {
#         'ENGINE': 'django.db.backends.mysql',
#         'NAME': 'crm_db',
#         'USER': 'root',
#         'PASSWORD': 'yourpassword',
#         'HOST': 'localhost',
#         'PORT': '3306',
#     }
# }

# 6️⃣ Apply migrations
python manage.py migrate

# 7️⃣ Run the development server
python manage.py runserver




```
## 🧠 What I Learned

Through this project, I strengthened my skills in:
- **Building full-stack web applications** with Django  
- **Integrating MySQL databases** with Django ORM  
- **Implementing authentication systems**  
- **Creating reusable templates and models**  
- **Deploying and managing backend apps**


