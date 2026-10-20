Smart Lab Asset Management System

A Python-based desktop application designed to simplify laboratory asset management and computer issue tracking.

About the Project

The Smart Lab Asset Management System helps manage laboratory computer assets and handle complaints efficiently. It provides a centralized interface for tracking assets, reporting technical issues, and managing complaint status.

Features

- Asset Management: Add, view, and manage laboratory assets.
- Issue Reporting: Allow students to report computer-related problems.
- Complaint Management: Track and update complaint status.
- Duplicate Complaint Prevention: Prevent duplicate reports for the same computer and issue.
- Dashboard: View important asset and complaint information.
- Search Functionality: Search assets using relevant details.
- CSV Export: Export asset information for record keeping.
- Login System: Provide a login interface for lab assistants.

Technologies Used

- Python
- Tkinter and ttk
- MySQL
- XAMPP and phpMyAdmin
- Pillow
- Pandas

Project Structure

Smart-Lab-Asset-Management-System/
  main.py
  db.py
  models.py
  README.md

Requirements

- Python 3
- MySQL Server
- Required Python libraries

Installation and Setup

1. Clone this repository:
   
   https://github.com/Vrushali2406/Smart-Computer-Lab-Assist

2. Open the project folder in VS Code.

3. Install the required libraries:
   
   python -m pip install mysql-connector-python pillow pandas

4. Start MySQL using XAMPP.

5. Create and configure the required database and tables according to the project source code.

6. Check the database connection settings in "db.py".

Run the Application

Run the following command from the project folder:

python main.py

Project Purpose

This project aims to reduce manual effort in laboratory asset tracking, improve complaint handling, and make lab maintenance more organized.

Future Enhancements

- Generate detailed maintenance reports.
- Add role-based access control.
- Improve security and input validation.
- Package the application for easier installation.

Author

Computer Science and Engineering Student

