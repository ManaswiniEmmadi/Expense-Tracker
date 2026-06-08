# Expense Tracker

A small Flask web app for tracking personal expenses and visualizing spending.

## Project Overview

This project lets you:
- Add expense entries with description, amount, category, and date
- Filter expenses by date range and category
- View total spending for the current filter
- See chart data for spending by category and spending over time
- Delete expense records
- Edit expense entries

The app stores data locally using SQLite (`expense.db`) and uses Flask + SQLAlchemy on the backend.

## Tech Stack

- Python
- Flask
- Flask-SQLAlchemy
- SQLite
- Jinja2 templates
- Tailwind CSS via CDN
- Chart.js for charts

## Setup

1. Create and activate your virtual environment:

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install flask flask_sqlalchemy
```

3. Run the app:

```powershell
python app.py
```

4. Open the app in your browser:

```text
http://127.0.0.1:5000/
```

## Screenshots

```markdown
![Dashboard screenshot](screenshots/dashboard.png)
<img width="1919" height="977" alt="dashboard" src="https://github.com/user-attachments/assets/87a25e1f-1720-4c1e-be8f-9a7b9ea226f5" />

![Add Expense screenshot](screenshots/add_expense.png)
<img width="1491" height="464" alt="add_expense" src="https://github.com/user-attachments/assets/27574a49-5b31-43df-9afc-8e2b801bd705" />

![Filters screenshot](screenshots/filters.png)
<img width="1421" height="300" alt="filters" src="https://github.com/user-attachments/assets/14df148b-63ae-42dd-9941-6f4ced60e7a0" />

![List Expenses screenshot](screenshots/list_expenses.png)
<img width="1550" height="579" alt="list_expenses" src="https://github.com/user-attachments/assets/3e491755-28f1-4fe9-8aba-9952014d8c1b" />

![Edit Expense screenshot](screenshots/edit_expense.png)
<img width="942" height="537" alt="edit_expense" src="https://github.com/user-attachments/assets/427d1bdf-b674-4e14-a2ce-ce027215fac3" />

![Charts screenshot](screenshots/charts.png)
<img width="1484" height="772" alt="charts" src="https://github.com/user-attachments/assets/9ee3c5c6-a5a0-4ae1-a14f-e41cdd8b281e" />

```
