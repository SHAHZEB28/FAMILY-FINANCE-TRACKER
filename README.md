# Family Finance Tracker

[![Live Site](https://img.shields.io/badge/Live_Site-View_App-28a745?style=for-the-badge)](https://unified-family-finance-tracker.onrender.com/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge&logo=github)](https://github.com/SHAHZEB28/FAMILY-FINANCE-TRACKER)

A comprehensive and user-friendly web application designed to help families track, manage, and unify their finances. Built with a robust Flask backend and a clean, dynamic frontend.

![Family Finance Tracker Screenshot](static/images/finance-tracker-screenshot.jpeg)

## Overview

The Family Finance Tracker is a full-stack web application that provides a centralized dashboard for managing household expenses and savings. Users can easily add, edit, and delete transactions, view summaries of their spending, and manage budgets. The application is built with a Python Flask backend, uses SQLAlchemy for database management, and features a responsive frontend created with standard HTML, CSS, and JavaScript.

## Live Demo

You can access the live, deployed application here:
**[https://unified-family-finance-tracker.onrender.com/](https://unified-family-finance-tracker.onrender.com/)**

## Key Features

* **Expense Management**: Seamlessly add, edit, and delete expenses with details like category, description, and amount.
* **Interactive Dashboard**: View key financial metrics at a glance, including total spending, expense counts, and top spending categories.
* **Data Persistence**: All financial data is securely stored in a SQLite database, managed via the powerful SQLAlchemy ORM.
* **Date Filtering**: Easily filter the expense list to view transactions within a specific date range.
* **Clean & Responsive UI**: A modern and intuitive user interface that provides a great user experience on both desktop and mobile devices.
* **Super User Controls**: Includes dedicated dashboards and management panels for administrative oversight.

## Tech Stack

This project was built using a classic and reliable set of web technologies.

| **Component** | **Technology** |
| :--- | :--- |
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white) |
| **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) |
| **Database** | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) |
| **Deployment** | ![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white) |

## Getting Started

To run this project locally, you will need to have Python and `pip` installed on your machine.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/SHAHZEB28/FAMILY-FINANCE-TRACKER.git](https://github.com/SHAHZEB28/FAMILY-FINANCE-TRACKER.git)
    cd FAMILY-FINANCE-TRACKER
    ```

2.  **Create and activate a virtual environment** (recommended):
    ```bash
    # For Windows
    python -m venv .venv
    .venv\Scripts\activate

    # For macOS/Linux
    python3 -m venv .venv
    source .venv/bin/activate
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Flask application:**
    ```bash
    python app.py
    ```

5.  **Open the application** in your browser at the provided URL, usually `http://127.0.0.1:5000`.

---
