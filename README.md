# Local Library  
A web application for managing a local library. It allows users to browse books, view details, and manage their book rentals. Built with Django framework.  

## 📌 Demo  
![Local Library Demo](https://raw.githubusercontent.com/omidranjbaran/locallibrary/master/locallibrary.gif)  

## 🚀 Features  
- 📚 **Book Catalog**: View a list of books, their details, and authors.  
- 🔄 **Book Rentals**: Users can view and renew their rented books.  
- 🛠 **Admin Panel**: Admins can manage books, authors, and users.  
- 🔑 **User Authentication**: Users can register, log in, and access their borrowed books.  

## 📦 Requirements  
- 🐍 **Python 3.x**  
- 🎯 **Django 3.x**  
- 🗄 **SQLite3** (default database)  

## 🔧 Installation  
Clone the repository:  
```bash
git clone https://github.com/omidranjbaran/locallibrary.git
cd locallibrary
```
Create a virtual environment and install dependencies:

```bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
pip install -r requirements.txt
```
Run database migrations:

```bash
python manage.py migrate
```
Create a superuser for admin access:

```bash
python manage.py createsuperuser
```
Start the development server:

```bash
python manage.py runserver
```

Now, open http://127.0.0.1:8000/ in your browser.
