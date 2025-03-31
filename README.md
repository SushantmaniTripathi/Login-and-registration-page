
# Login and Registration System with Flask  

This is a simple web-based authentication system that includes user registration, login, and access to a protected page using Flask, SQLite, and Flask-Login.  

# Features  

- User registration with password hashing  
- Secure login authentication  
- Protected page accessible only after login  
- Logout functionality  
- Flash messages for user feedback  

# Technologies Used  

- **Backend**: Flask (Python)  
- **Frontend**: HTML, CSS (templates assumed to be provided)  
- **Database**: SQLite  
- **Security**: Password hashing with `werkzeug.security`  

# Installation  

1. Clone this repository:  

   ```bash
   git clone https://github.com/sushantmani-tripathi/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies using:  

   ```bash
   pip install flask flask-sqlalchemy flask-login werkzeug
   ```

3. Run the application:  

   ```bash
   python main.py
   ```

4. Open your browser and go to:  

   ```
   http://127.0.0.1:5000/
   ```

# Project Structure  

```
/project-folder
│── main.py              # Main Flask application
│── templates/
│   ├── index.html       # Homepage
│   ├── register.html    # Registration page
│   ├── login.html       # Login page
│   ├── secrets.html     # Protected page
│── static/              # CSS and other static files
│── users.db             # SQLite database (generated after first run)
```
# project glimpse













# Usage  

- Visit `/register` to create an account.  
- Login at `/login`.  
- After login, access the protected page at `/secrets`.  
- Logout via `/logout`.  

# Author  

Developed by Sushantmani Tripathi 
GitHub: [sushantmani-tripathi](https://github.com/sushantmani-tripathi)  

# License  

This project is for educational purposes. Feel free to modify and contact me!  

Let me know if you need any help ! 🚀
