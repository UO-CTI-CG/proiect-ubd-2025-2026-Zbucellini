PassPal 🔐

PassPal is a web-based password management application developed as part of a university project.
The application provides a simple and intuitive interface for storing, organizing, and generating passwords securely.

The project focuses on understanding web application structure, authentication flows, and data handling using Python and Flask.

🎓 Project Purpose

Academic coursework / university assignment

Learning Flask application architecture

Practicing backend–frontend integration

Understanding user authentication and data persistence

This project is intended strictly for educational purposes.

✨ Features

User registration and authentication

Secure storage of password entries

Password generator utility

Search functionality for saved entries

Export functionality for stored data

Responsive user interface

Custom branding and favicon (PassPal)

🛠 Technologies Used

Backend: Python, Flask

Frontend: HTML, Jinja2, Bootstrap

Database: SQLite

Icons: Bootstrap Icons

Styling: Custom CSS

Deployment support: wsgi.py, Procfile

📁 Project Structure
.
├── app/
│   ├── entries/
│   ├── errors/
│   ├── main/
│   ├── users/
│   ├── static/
│   │   ├── icons/
│   │   ├── images/
│   │   └── style.css
│   ├── templates/
│   │   ├── errors/
│   │   ├── account.html
│   │   ├── add.html
│   │   ├── export.html
│   │   ├── generator.html
│   │   ├── index.html
│   │   ├── layout.html
│   │   ├── signin.html
│   │   └── signup.html
│   ├── models.py
│   └── config.py
├── app.py
├── wsgi.py
├── requirements.txt
├── Procfile
└── README.md

🚀 Running the Application Locally
1. Clone the repository
git clone https://github.com/<your-username>/passpal.git
cd passpal

2. Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate   # Linux/macOS
.venv\Scripts\Activate.ps1      # Windows

3. Install dependencies
pip install -r requirements.txt

4. Run the application
python app.py


The application will be available at:

http://127.0.0.1:5000

⚠️ Disclaimer

PassPal is a student project and is not intended for production use.
It should not be used to store real or sensitive passwords.