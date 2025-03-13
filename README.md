
# 📚 Book Manager  
A web application built with Django for managing a local library. It allows users to browse books, view details, and manage their book rentals.

## 📌 Demo  
![Local Library Demo](https://raw.githubusercontent.com/omidranjbaran/locallibrary/master/locallibrary.gif)  

## 🚀 Features  
- 📚 **Book Catalog**: Browse a collection of books, explore their details, and discover authors.  
- 🔄 **Book Rentals**: Users can easily view and renew their rented books.  
- 🛠 **Admin Panel**: Admins can efficiently manage books, authors, and users.  
- 🔑 **User Authentication**: Secure registration, login, and access to users' borrowed books.  

## 📦 Requirements  
- 🐍 **Python 3.x**  
- 🎯 **Django 3.x**  
- 🗄 **SQLite3** (default database)  

## 🔧 Installation  
1. **Clone the repository**:  
```bash
git clone https://github.com/omidranjbaran/locallibrary.git
cd locallibrary
```

2. **Create a virtual environment and install dependencies**:  
```bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
pip install -r requirements.txt
```

3. **Run database migrations**:  
```bash
python manage.py migrate
```

4. **Create a superuser for admin access**:  
```bash
python manage.py createsuperuser
```

5. **Start the development server**:  
```bash
python manage.py runserver
```

6. **Access the app**:  
Now, open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser to explore the Local Library!

---

✨ **Enjoy managing your books and rentals with the Book Manager App!**
