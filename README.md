# The Flask Journal

A simple blog web application built with Flask and SQLAlchemy. Users can register, log in, create, update, and delete blog posts. The app uses SQLite for data storage and features a modern, responsive UI.

## Features

- User registration and authentication
- Create, read, update, and delete blog posts
- Secure password hashing
- Session management
- Responsive design with Jinja2 templates

## Project Structure

```
flask_journal/
├── app.py                # Main application file
├── config.py             # Configuration settings
├── models.py             # Database models
├── forms.py              # Web forms
├── templates/            # HTML templates
│   ├── layout.html       # Base layout
│   ├── index.html        # Homepage
│   ├── login.html        # Login page
│   ├── register.html     # Registration page
│   ├── dashboard.html    # User dashboard
│   └── post.html         # Blog post page
└── static/              # Static files (CSS, JavaScript, images)
    ├── css/
    │   └── styles.css    # Custom styles
    ├── js/
    │   └── scripts.js     # Custom JavaScript
    └── images/           # Image files
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flask_journal.git
   cd flask_journal
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up the database:
   ```bash
   from app import db
   db.create_all()
   ```
5. Run the application:
   ```bash
   python app.py
   ```
6. Access the app in your web browser at `http://127.0.0.1:5000/`.

## Usage

- Register a new account or log in with an existing account.
- Create, view, edit, and delete your blog posts.
- Explore the homepage to see recent posts.
- Visit the user dashboard to manage your profile and posts.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/my-feature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add my feature"
   ```
4. Push to your forked repository:
   ```bash
   git push origin feature/my-feature
   ```
5. Create a pull request describing your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy blogging with The Flask Journal!

