# Library Management Web App

## Overview
This project is a full-stack web application developed using Flask for managing a library system.  
It allows authenticated users to manage books, customers, inventory, and sales through a web interface.

## Features
- User authentication (login system)
- Book catalog management
- Inventory (stock) tracking
- Customer (contacts) management
- Sales history tracking
- Search functionality for books and customers
- Public-facing page with available books

## Technologies
- Python (Flask)
- MySQL
- HTML
- CSS
- JavaScript
- Bootstrap

## Database Structure
The application is built on a relational MySQL database, including the following main tables:
- **Contacts**: stores users and customers
- **Books**: book catalog with details
- **Stock**: number of available copies
- **Sales**: transaction history
- **Recapiti (Contacts details)**: additional contact information

The database is designed to be normalized and scalable.
