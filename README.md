# Basic site with full user management functionality
### Created with Django

A basic site where users can register, log in, reset and change passwords, and log out. The site allows users to send password reset emails and authenticate using GitHub as an external service. 

---

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required environment.

```bash
pip install -r requirements.txt
```

The admin logins are:
- username: tompain
- password: Hello123 

---

## Running the programme as a web application

To start the application:

```bash
$ python manage.py runserver
```

Reset password emails will only send to hello@tompa.in as this site is connected to a sandbox version of Mailgun and will only send if you have the EMAIL_HOST_USER and EMAIL_HOST_PASSWORD saves as environmental variables. 

For social logins, you must be viewing the site on http://localhost:8000/

---

## Project Components

The project contains two apps, the main iam_project app along with the user app
