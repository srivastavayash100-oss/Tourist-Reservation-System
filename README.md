Tourist Reservation System (C++)
[2nd-Year Academic Project | Group of 3] 

📌 Project Overview
This is a console-based application designed to automate travel booking processes through persistent data storage and Object-Oriented Programming (OOP).

💡 Implementation Details

Core Reservation Logic: Developed the Tourist class to handle both Admin and User functionalities, including trip creation and reservation management.


Data Persistence: Implemented custom pack and unpack functions using fstream to store trip and reservation records in pipe-separated format (|) within Trip.txt and Reservation.txt.


Modular Payment Gateway: Architected an abstract Payment class with a pure virtual function processPayment().


Polymorphism: Used runtime polymorphism to handle CreditCardPayment and PayPalPayment subclasses for a scalable payment structure.

🛠️ Tech Stack & Concepts

Language: C++.


File Handling: fstream for persistent storage and data packing/unpacking.


OOPs Principles: Inheritance, Polymorphism (Virtual Functions), and Encapsulation.
