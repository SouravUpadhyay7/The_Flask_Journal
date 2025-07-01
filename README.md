# The Flask Journal






https://github.com/user-attachments/assets/4045dca1-d368-47ea-9224-5279cdbf9ca5



![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

A simple blog web application built with Flask and SQLAlchemy. Users can register, log in, create, update, and delete blog posts. The app uses SQLite for data storage and features a modern, responsive UI.

## Features

- **User Authentication**: Secure user registration and login system
- **Blog Management**: Create, read, update, and delete blog posts
- **Security**: Secure password hashing with industry standards
- **Session Management**: Robust user session handling
- **Responsive Design**: Modern UI built with Jinja2 templates
- **Database Integration**: SQLAlchemy ORM with SQLite backend

## Technology Stack

- **Backend**: Flask (Python web framework)
- **Database**: SQLite with SQLAlchemy ORM
- **Frontend**: HTML5, CSS3, Jinja2 templating
- **Authentication**: Flask session management with secure password hashing

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SouravUpadhyay7/The_Flask_Journal.git
   cd The_Flask_Journal
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the database**
   ```bash
   flask db init
   flask db migrate -m "Initial migration"
   flask db upgrade
   ```

5. **Run the application**
   ```bash
   python app.py
   ```

The application will be available at `http://localhost:5000`

## Usage

- **Register**: Create a new account with username, email, and password
- **Login**: Access your account with existing credentials
- **Dashboard**: Manage your profile and view your posts
- **Create Posts**: Write and publish new blog entries
- **Edit Posts**: Update your existing blog posts
- **Delete Posts**: Remove posts you no longer want
- **Explore**: Browse the homepage to discover recent posts from all users



## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request



## Author

**Sourav Upadhyay**
- GitHub: [@SouravUpadhyay7](https://github.com/SouravUpadhyay7)

## Acknowledgments

- Flask community for the excellent web framework
- SQLAlchemy for the powerful ORM
- All contributors who help improve this project
