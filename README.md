# AirBnB Clone Project

## Description

Welcome to the AirBnB clone project! This project is the first step towards building a full web application that emulates the functionality of AirBnB. The primary goal of this initial phase is to develop a command interpreter to manage AirBnB objects. This includes creating a parent class (BaseModel) for object initialization, serialization, and deserialization, as well as implementing a simple flow of serialization/deserialization involving Instance <-> Dictionary <-> JSON string <-> file. The project also involves creating specific classes for AirBnB entities (User, State, City, Place) and establishing the first abstracted storage engine (File storage).

## Command Interpreter

### Definition

The command interpreter in this project is akin to a Shell but tailored to the specific needs of managing AirBnB objects. It allows users to:

- Create new objects (e.g., User, Place)
- Retrieve objects from files or databases
- Perform operations on objects (e.g., counting, computing stats)
- Update attributes of an object
- Destroy an object

### How to Start

To start the command interpreter, follow these steps:

1. Clone the project repository to your local machine:

   ```bash
   git clone https://github.com/your-username/AirBnB-Clone.git
Navigate to the project directory:

bash
Copy code
cd AirBnB-Clone
Run the command interpreter:

bash
Copy code
python console.py
How to Use
Once the command interpreter is running, you can interact with it by entering commands. The supported commands include, but are not limited to:

create: Create a new object
show: Show details of a specific object
destroy: Destroy an object
all: Display all objects
...
Examples
Creating a new User:

bash
Copy code
(cmd) create User
Showing details of a Place:

bash
Copy code
(cmd) show Place 1234-5678
Destroying a State:

bash
Copy code
(cmd) destroy State 9876-5432
Displaying all Users:

bash
Copy code
(cmd) all User
