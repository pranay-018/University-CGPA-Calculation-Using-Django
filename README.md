# University-CGPA-Calculation-Using-Django
The CGPA Calculator is a web-based application designed to assist students in calculating their Cumulative Grade Point Average (CGPA) efficiently and securely. CGPA is a critical metric that reflects a student's overall academic performance by averaging grade points across multiple subjects. 

This project demonstrates how to build a secure CGPA calculator using Django. Users can register, log in, and input their subject names, CGPA, and credits. The calculator then computes the cumulative GPA and allows the results to be printed in PDF format.

## Features
- User registration and login system for secure access.
- Input fields for subjects, CGPA, and credits.
- CGPA calculation and result generation.
- PDF export functionality for results.

## Requirements
- Python 3.x
- Django 4.x
- ReportLab (for PDF generation)

## Tech Stacks
Django, Python, HTML, CSS

## Running this project
To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with

pip install virtualenv

Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

virtualenv env

That will create a new folder env in your project directory. Next activate it with this command on mac/linux: source env/bin/active

Then install the project dependencies with pip install -r requirements.txt

Now you can run the project with this command python manage.py runserver

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cgpa-calculator.git
   cd cgpa-calculator
## Project ScreenShots
Login Page
![{1EC283C5-EDC8-416A-A713-25A4D2A8C8F2}](https://github.com/user-attachments/assets/7f66cc34-a98f-4f63-9cbb-0af85dec0100)

Adding Subjects

![{A1FC1C93-7577-45EC-B797-416158189B5B}](https://github.com/user-attachments/assets/74cf8719-8b9b-4c0b-98f9-409b8d9c630f)

Editing Subjects

![{C14D5031-EE47-46A2-9F8A-6686A65A21D7}](https://github.com/user-attachments/assets/78d1a00a-104b-4bb2-ac9b-36bb38694c7a)


Generating Result

![{83FDE487-AFB8-43CE-B995-1B278191E455}](https://github.com/user-attachments/assets/3bcf4d4b-a20c-49fd-b872-d4c53d6ac600)

Printing PDF

![{DC02A889-59D1-446D-8282-36CC907EFF08}](https://github.com/user-attachments/assets/a1a42fc3-89f4-4d0d-8c6a-db62d70a20d9)



