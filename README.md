#  Personal Expense Tracker

[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/ML-Enabled-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)

##  Overview

This is a **personal expense tracker web application** built using Django. It allows users to log their expenses, categorize them, and provides automated expense categorization and future expense prediction features powered by machine learning. Take control of your finances with intelligent insights and easy-to-use expense management tools.

---

##  Features

###  Expense Logging
Easily log your daily expenses, including the date, description, amount, and category.

###  Automated Expense Categorization
The application uses machine learning algorithms to automatically categorize expenses based on their descriptions. This makes it easier to track and manage your spending without manual categorization.

###  Future Expense Prediction
Get predictions for future expenses based on your spending history. This can help you plan your budget more effectively and make informed financial decisions.

###  User Authentication
Users can create accounts and log in to securely manage their expenses. Each user's data is private and protected.

### 📈 Dashboard & Analytics
- Visual representation of spending patterns
- Category-wise expense breakdown
- Monthly/yearly spending trends
- Budget tracking and alerts

---

##  Tech Stack

| Component          | Technology                     |
|--------------------|--------------------------------|
| **Framework**      | Django                         |
| **Language**       | Python 3.x                     |
| **Database**       | SQLite (default) / PostgreSQL  |
| **ML Libraries**   | Scikit-learn, Pandas, NumPy    |
| **Frontend**       | HTML, CSS, JavaScript, Bootstrap|
| **Authentication** | Django Auth System             |

---

##  Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.8 or higher
- pip (Python package manager)
- Git

---

##  Setup

Follow these steps to run the application locally:

### 1. Clone the Repository

```bash
git clone https://github.com/Harikesh-Das/personal-expense-tracker.git
cd personal-expense-tracker
```

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**Windows:**
```bash
venv\Scripts\activate
```

**macOS and Linux:**
```bash
source venv/bin/activate
```

### 4. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

### 6. Create a Superuser Account

```bash
python manage.py createsuperuser
```

Follow the prompts to set up your admin credentials.

### 7. Start the Development Server

```bash
python manage.py runserver
```

### 8. Access the Application

Open your web browser and navigate to:
```
http://localhost:8000
```

---

##  Usage

### Getting Started

1. **Create an Account**: Register a new account or log in using your superuser credentials
2. **Add Expenses**: Click the "Add Expense" button to log a new expense
3. **Fill Details**: Enter the date, description, amount, and category
   - Leave the category empty for automatic ML-powered categorization
4. **View Dashboard**: Access your expense history, categorized expenses, and future predictions
5. **Admin Panel**: Go to `http://localhost:8000/admin/` to manage users, categories, and database

---

##  Contributing

In case you wanna contribute 😁, Please follow these steps:

### 1. Fork the Repository

Click the "Fork" button on GitHub

### 2. Create a Feature Branch

```bash
git checkout -b feature/AmazingFeature
```

### 3. Make Your Changes

Write clean, documented code following Django best practices

### 4. Commit Your Changes

```bash
git commit -m "Add: Amazing new feature"
```

### 5. Push to Your Fork

```bash
git push origin feature/AmazingFeature
```

### 6. Open a Pull Request

Submit a PR with a clear description of your changes
---

<div align="center">

Thanks for your contributions! 😁

</div>
