# Library Management System

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Database Design](#database-design)
- [GUI Design](#gui-design)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Overview
The Library Management System is a software application designed to efficiently manage the operations of a library. It provides functionalities for inserting, displaying, searching, and modifying book records. The system utilizes a database management system (DBMS) to ensure data security, ACID properties (Atomicity, Consistency, Isolation, Durability), and automatic file synchronization with the database.

## Features
- Insert new book records into the library database
- Display book details and availability status
- Search for books based on book ID
- Modify book records, including issuing and returning books
- User-friendly graphical user interface (GUI) for enhanced interaction

## Technologies Used
- Python programming language
- MySQL database management system
- Tkinter library for GUI development
- PyMySQL library for MySQL database connectivity

## Database Design
The library management system utilizes a MySQL database to store and manage book records. The database schema includes tables for storing book details, such as book ID, title, author, and availability status. The system interacts with the database using SQL queries to perform operations like inserting, retrieving, updating, and deleting book records.

## GUI Design
The graphical user interface (GUI) of the library management system is developed using the Tkinter library in Python. The GUI provides an intuitive and user-friendly interface for librarians and users to interact with the system. It includes windows, frames, labels, entry fields, and buttons for various functionalities such as adding books, displaying book details, searching for books, and modifying book records.

## Installation
1. Clone the repository: https://github.com/Akalbir17/Library-Management-System

2. Install the required dependencies: `pip install -r requirements.txt`

3. Set up the MySQL database:
- Create a new database for the library management system
- Update the database connection details in the code (`main.py`)

## Usage
1. Run the main program: `python main.py`

2. The main window of the library management system will appear.

3. Use the provided buttons to navigate and perform various operations:
- Add Book: Enter book details and click "Submit" to add a new book to the database
- Delete Book: Enter the book ID and click "Submit" to delete a book from the database
- View Book: Click "View" to display all the books present in the database
- Issue/Return Book: Enter the book ID and click "Issue" or "Return" to modify the book's availability status
- Search Book: Enter the book ID and click "Search" to check if the book is present in the database

4. Follow the on-screen instructions and prompts to interact with the system.

## Screenshots
![Main Window](![image](https://github.com/Akalbir17/Library-Management-System/assets/69676151/1940f243-66f5-49a6-9c77-edbf7ddd9689))
*Main Window of the Library Management System*

![Add Book](![image](https://github.com/Akalbir17/Library-Management-System/assets/69676151/f7162caa-677c-4ef8-a164-a52ac3a90453))
*Adding a New Book to the Database*

![View Books](![image](https://github.com/Akalbir17/Library-Management-System/assets/69676151/93d18d9f-d09f-4ce3-b390-f1039da39a30))
*Displaying All Books in the Database*

![Search Book](![image](https://github.com/Akalbir17/Library-Management-System/assets/69676151/f3cd1253-3799-4294-9be8-334a23ccb31f))
*Searching for a Book by Book ID*

![Issue/Return Book](![image](https://github.com/Akalbir17/Library-Management-System/assets/69676151/8ff7d4e2-2776-4a45-94f8-1d5eedc3362a))
*Issuing or Returning a Book*

## Contributing
Contributions to the Library Management System project are welcome. If you find any bugs, have suggestions for improvements, or want to add new features, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
