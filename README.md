# Flask Blog Application

This is a Flask-based web application for a simple blogging platform. Users can register, log in, create, edit, and delete blog posts, as well as leave comments on posts. Additionally, there are features for administrative tasks like managing posts.

## Features

- **User Authentication:** Users can register with unique email addresses and log in securely.
- **CRUD Operations:** Users can create, read, update, and delete their blog posts.
- **Comments:** Users can leave comments on blog posts.
- **Admin Privileges:** Admin users have additional privileges such as editing or deleting any post.
- **Contact Form:** Provides a simple contact form to send messages to the site administrator.

## Installation

1. Clone this repository to your local machine.
2. Install the required Python packages using `pip install -r requirements.txt`.
3. Set up environment variables for `EMAIL`, `PASSWORD`, and `KEY` as per your requirements.
4. Optionally, set up a database URI for `DB_URI` in your environment variables.
5. Run the application using `python app.py`.

## Usage

- Visit `/register` to create a new account or `/login` to log in to an existing account.
- Once logged in, only admin users can navigate to `/new-post` to create a new blog post.
- Users can view all posts on the homepage (`/`) and click on individual posts to view details.
- Admin users can access administrative features such as editing or deleting posts by visiting `/edit-post/<post_id>` or `/delete/<post_id>` respectively.
- Users can also leave comments on blog posts by visiting `/post/<post_id>`.

## Hosted Website

The application is hosted and accessible at [https://blog-site-gjcl.onrender.com/](https://blog-site-gjcl.onrender.com/).


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

