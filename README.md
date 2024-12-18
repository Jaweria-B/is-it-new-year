# **Is It New Year?**

**Question:** *Is it new year?* -- I know. Such a big mystery question to be answered, right?


### **Description**
"Is It New Year?" is a simple Python and Django web application that answers the age-old question: **"Is it New Year?"**. With a straightforward interface and functionality, this project is a perfect introduction to building web applications with Django.

---

### **Features**
- **Simple Question-Answer Logic**: The app determines whether today is New Year’s Day and displays the result.
- **Django Framework**: Utilizes Django to set up views, URLs, and an HTTP server for local testing.
- **Minimalist Design**: Focuses on functionality rather than design complexity.

---

### **Technologies Used**
- Python 3.x
- Django Framework

---

### **Installation and Usage**

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Jaweria-B/is-it-new-year.git
   cd is-it-new-year
   ```

2. **Set Up a Virtual Environment (Optional but Recommended)**  
   ```bash
   python -m venv env
   source env/bin/activate   # On Linux/Mac
   env\Scripts\activate      # On Windows
   ```

3. **Install Dependencies**  
   Ensure Django is installed in your environment:  
   ```bash
   pip install django
   ```

4. **Run the Development Server**  
   Use the following command to start the Django server:  
   ```bash
   python manage.py runserver
   ```

5. **Access the Application**  
   Open your web browser and navigate to:  
   ```
   http://127.0.0.1:8000/isitnewyear
   ```

---

### **Project Structure**
```
is-it-new-year/
├── .github/                     # GitHub-specific files and workflows
├── is_it_new_year/              # Main Django project folder
│   ├── __pycache__/             # Compiled Python files
│   ├── __init__.py              # Package initialization
│   ├── asgi.py                  # ASGI configuration
│   ├── settings.py              # Django settings
│   ├── urls.py                  # Project-level URL configurations
│   ├── wsgi.py                  # WSGI configuration
├── new_year/                    # Django app folder
│   ├── __pycache__/             # Compiled Python files
│   ├── migrations/              # Database migrations folder
│   │   └── __pycache__/         # Compiled migration files
│   ├── static/newyear/          # Static files (CSS, images, etc.)
│   │   └── styles.css           # Custom styles
│   ├── templates/newyear/       # HTML templates
│   │   └── index.html           # Main template file
│   ├── __init__.py              # App initialization
│   ├── admin.py                 # Admin panel configuration
│   ├── apps.py                  # App-specific configurations
│   ├── models.py                # Database models (not used in this project)
│   ├── tests.py                 # Unit tests
│   ├── urls.py                  # App-level URL configurations
│   ├── views.py                 # App logic and views
├── db.sqlite3                   # SQLite database file
├── manage.py                    # Django management script
├── README.md                    # Project README file

```

---

### **How It Works**
1. The app uses Django's routing to direct users to `/isitnewyear`.
2. A Python script checks the current date to determine if it's January 1st.
3. The result is displayed on the webpage.

---

### **Future Enhancements**
- Add a countdown to the next New Year’s Day.
- Localize the app to support different time zones.
- Enhance the front-end design with CSS and JavaScript.

---

### **License**
This project is licensed under the [MIT License](LICENSE).

---

Let me know if you’d like further tweaks or additions!