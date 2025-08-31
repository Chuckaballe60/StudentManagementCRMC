# School-Management-System-Python-MySQL

Project Description:

The School Management System is a comprehensive software application designed to streamline the recording of student admissions and student records with Python and MySQL database connectivity. It simplifies the process of managing various aspects related to new student admissions, entering student records, and displaying this information. This system is tailored to make the entry and retrieval of data an effortless task.

Features:

1. Main Menu: The system initiates with a user-friendly main menu, providing options for Admission, Student Data, and an Exit option to leave the system.

2. Admission Module: This module allows administrators to manage student admissions. It provides the following options:
    - Admission Details: The system captures and stores information about new student admissions, including admission number, roll number, student name, address, phone number, and class.
    - Show Admission Details: It displays a list of all admission records.
    - Search: Administrators can search for admission details using the admission number.
    - Deletion of Records: Admission records can be deleted based on the admission number.
    - Update Admission Details: This option allows administrators to modify admission details, such as names, addresses, and phone numbers.

3. Student Data Module: This module focuses on student records management, offering the following options:
    - Add Student Record: The system facilitates the addition of records of enrolled students, including academic session, student name, class, section, roll number, and subject details.
    - Show Student Details: It displays a list of all student records.
    - Search Student Record: Administrators can find student records by providing the roll number.
    - Delete Student Records: Student records can be deleted based on the roll number.
    - Edit Student Record: The system allows administrators to edit various attributes of student records, such as session, name, class, section, roll number, and subject details.

Database Connectivity:
The system is seamlessly integrated with a MySQL database, ensuring data integrity and security. It allows for the efficient storage and retrieval of student admission and student record information.

How to Use:
- The system is initiated, and it presents a main menu with options for admission and student data management.
- Users select the desired option by entering the corresponding choice number.
- They follow the on-screen prompts to perform actions such as adding, viewing, searching, updating, or deleting student records.

This School Management System offers a comprehensive solution for managing student admissions and records, simplifying the administrative tasks of Mao Public School. With the power of Python and MySQL, it ensures data accuracy and accessibility, making the management of student information efficient and reliable.


FOR YOUTUBE RESOURCES TO PRACTICE

https://www.youtube.com/watch?v=elWvom3F2tQ&t=16s

✨ Features
Add new records: Insert details like name, address, phone number, age, and gender into the database.

Delete records: Remove records from the database by specifying a user name.

Update records: Modify details such as name, address, phone number, age, or gender for an existing record.

View all records: Retrieve and display all entries stored in the database.

Interactive menu: Simple text-based interface for smooth navigation.

🛠️ Requirements

Python 3.x

MySQL Server

MySQL Connector for Python (mysql-connector-python)

🚀 Setup Instructions

Clone the Repository

git clone <repository-url>

cd <repository-folder>

Install Required Libraries Install the MySQL Connector library using pip:

pip install mysql-connector-python

Set Up the MySQL Database

Create a database in MySQL named Ak1:

CREATE DATABASE Ak1;

Create the required table:

CREATE TABLE ShopperLog (

    name VARCHAR(255),
    
    address VARCHAR(255),
    
    phone VARCHAR(10),
    
    age VARCHAR(100),
    
    gender VARCHAR(255)
);
Update Database Credentials Open the Python script and update the following section with your MySQL credentials:

mydb = mysql.connector.connect(
    host="localhost",
    user="root",
    password="your_password",
    database="Ak1"
)
Run the Application Execute the script in your terminal:

python your_script_name.py

Follow the Menu Options Use the menu displayed in the terminal to interact with the system.

📋 Usage
Launch the script.

Choose an option from the menu to add, delete, update, or view records.

Enter the required details as prompted.

Continue or exit as needed.    


