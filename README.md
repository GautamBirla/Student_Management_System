# Student_Management_System
Overview
The Student Management System is a web application built using Django, HTML, and CSS designed to simplify the management of student records for educational institutions. This project allows administrators to efficiently manage student data, including adding, editing, deleting, and filtering student information.

Features
Student CRUD Operations: Create, Read, Update, and Delete student records.
Advanced Filtering: Search students by Class, Session, Section, and Name.
Detailed Profiles: Retrieve student details using Registration No.
Fee Management: Automatically calculate Due Fees based on Total Fees and Paid Fees.
Responsive Design: User-friendly interface with a visually appealing layout.
Technology Stack
Django: Provides a powerful backend framework for handling CRUD operations and database management.
HTML/CSS: Utilized for creating a clean and responsive frontend.
Project Structure
student_management/: The Django project directory.

student_management/settings.py: Configuration settings for the Django project.
student_management/urls.py: URL routing for the project.
student_management/wsgi.py: WSGI configuration for deployment.
students/: The Django app directory for managing student-related functionalities.

models.py: Defines the data models for the application.
views.py: Contains the logic for handling requests and rendering responses.
urls.py: URL routing specific to the students app.
templates/: Contains HTML templates for rendering web pages.
add_student.html: Template for adding a new student.
edit_student.html: Template for editing student details.
view_students.html: Template for viewing all students.
filter_students.html: Template for filtering students based on various criteria.
static/: Contains CSS files for styling the application.

Navigate to the Project Directory:
cd student-management-system

Create and Activate a Virtual Environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install the Required Packages:
pip install -r requirements.txt

Apply Migrations:
python manage.py migrate

Run the Development Server:
python manage.py runserver

Access the Application:
Open your web browser and navigate to http://127.0.0.1:8000/ to use the Student Management System.

Acknowledgements
Django Framework for its powerful and flexible web development capabilities.
HTML and CSS for creating a responsive and user-friendly interface.
