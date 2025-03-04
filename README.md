## 📌 Blog Management Application

A web-based blogging platform built using Django, HTML, CSS, and Bootstrap. This application allows users to create, edit, and manage blog posts.

## 🚀 Features
- User authentication (Sign up, Login, Logout)
- CRUD operations for blog posts
- Commenting system
- Responsive UI with Bootstrap
- Django Admin Panel for user and post management

## 🛠 Tech Stack
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Django (Python)
- **Database:** SQLite

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/blog-management-app.git
cd blog-management-app
```

### 2️⃣ Create and Activate Virtual Environment
#### Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

#### Mac/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Create Superuser (Optional)
```bash
python manage.py createsuperuser
```

### 6️⃣ Run the Development Server
```bash
python manage.py runserver
```

## 🔮 Future Enhancements
- Like/Dislike system for blog posts
- User profile pages
- Tag-based filtering for posts
- Rich text editor for writing blogs
