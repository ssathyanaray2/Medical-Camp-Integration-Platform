# Medical Camp Integration Platform


# Overview
During a hackathon at JSS Science and Technology University, my team and I developed a web application using Django to assist NGOs in organizing medical camps. The platform enables NGOs to efficiently schedule camps, store and manage patients' medical histories, and connect with qualified doctors. The idea stemmed from firsthand experience attending a medical camp, where we identified key challenges faced by NGOs. Through this project, I gained valuable insights into full-stack development, industry-level coding standards, and real-world problem-solving. we named it sanjeevani described as a magical herb with the power to heal. We integrated facebook using facebook sdk so that NGO can upload an image along with infromation as an post. 

# Features
User Authentication & Authorization

Admin Dashboard for Camp Management

Patient Medical History Storage

Doctor Search & Matching

Django Models & ORM for Data Handling

Form Handling & Serialization

# Tech Stack
Backend: Django, Django REST Framework, Python

Database: SQLite/MySQL

Frontend: HTML, CSS, Bootstrap, Javascript

# Instruction to run:

1) Navigate to the folder:
cd sanjeevini

2) Setup the virtual environment:
python -m venv venv
source venv/bin/activate

3) Install packages:
pip install -r requirement.txt

4) create database migrations:
python manage.py migrate

5) create superuser for admin:
python manage.py createsuperuser 

6) Run Project
python manage.py runserver

# Usage
Admin Panel: /admin (Manage Camps, Doctors, Patients)
User Signup/Login: /signup, /login
Camp Listings: View & Register for Medical Camps

