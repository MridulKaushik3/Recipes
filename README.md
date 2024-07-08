# Recipes Web App

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Running the Project](#running-the-project)
- [Project Structure](#project-structure)
- [CRUD Operations](#crud-operations)
- [Authentication](#authentication)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Overview
The **Recipes Web App** is a Django-based project that allows users to create, read, update, and delete (CRUD) recipes. It includes user authentication for registering, logging in, and logging out.

## Features
- User registration and authentication
- Add new recipes
- View list of recipes
- Update existing recipes
- Delete recipes
- Upload images for recipes

## Technologies Used
- **Django**: Python web framework
- **Bootstrap**: Front-end framework for styling
- **SQLite**: Default database for Django (can be switched to another DBMS)


## Setup and Installation

### Prerequisites
- Python 3.8+
- pip (Python package installer)
- Virtualenv (recommended)

## Project Structure
recipes-web-app/
│
├── your_app/
│   ├── migrations/
│   ├── static/
│   │   └── your_app/
│   │       ├── css/
│   │       ├── js/
│   │       └── images/
│   ├── templates/
│   │   └── your_app/
│   │       ├── base.html
│   │       └── other_templates.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── media/
│   └── images/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/


