# Birthdays

A web application that allows users to store and manage birthdays. Built with Flask as part of Harvard's CS50 Introduction to Computer Science.

## Features

- Add new birthdays
- View a list of saved birthdays
- Store birthday records in a database

## Structure

```bash
cs50x-birthdays
├── templates
│   ├── error.html
│   ├── index.html
│   └── layout.html
│
├── static
│   └── styles.css
│
├── app.py
├── schema.sql
├── requirements.txt
└── README.md
```

## Technologies

- Python
- Flask
- SQLite
- HTML & CSS
- Jinja

## Running Locally

Clone the repository:

```bash
git clone https://github.com/bassam-alaraby/cs50x-birthdays.git
cd cs50x-birthdays
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Create the SQLite database from the schema file:

```bash
sqlite3 birthdays.db < schema.sql
```

Start the Flask development server:

```bash
flask run
```

Open the local URL provided by Flask in your browser.

## About

This project demonstrates web development with Flask, database operations, and handling user-submitted data.