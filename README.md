# WanderWord 🌍✍️

WanderWord is a powerful blogging platform designed for wanderers of words, built with Python, Flask, and Bootstrap. It provides a seamless experience for authors to craft captivating posts, while allowing registered users to engage through comments.

## Tech Stack

- **Frontend**: HTML, Bootstrap
- **Backend**: Python, Flask
- **Database**: PostgreSQL
- **ORM**: SQLAlchemy
- **Authentication**: Werkzeug.security
- **Text Editing**: CKEditor
- **User Avatars**: Gravatar

## Features

- **User Authentication**: Secure login system powered by Werkzeug.security with hashed passwords.
- **Admin Privileges**: Admin users can create, edit, and delete posts.
- **Rich Text Editing**: Utilizes CKEditor for text formatting, image insertion, and formatting.
- **Database Integration**: PostgreSQL database (from Raleway.app) managed via SQLAlchemy.
- **User Avatars**: Utilizes Gravatar for user avatar images.
- **Comments**: Registered users can engage by commenting on posts.

## Installation

1. Clone the repository: `git clone https://github.com/Saurabh13042004/WanderWord.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `python main.py`
4. Access the application at `http://localhost:5000/`.

## Usage

1. As an admin, log in to create, edit, or delete posts.
2. Registered users can comment on posts.

## Admin Details

- **Email**: admin@blog.me
- **Password**: admin123

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
