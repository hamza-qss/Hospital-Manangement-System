# Hospital-Manangement-System
An Advance Hospital management system written in C++.
Hospital Management System (C++)
A robust, console-based application designed to streamline hospital operations. This system manages patient records, doctor schedules, and appointment billing using Object-Oriented Programming (OOP) principles in C++.

 Features
Patient Management: Register new patients, update records, and view medical history.

Doctor Records: Maintain a database of specialized doctors and their availability.

Appointment Scheduling: Book, reschedule, or cancel appointments.

Billing System: Generate automated invoices for consultations and treatments.

Data Persistence: Uses File Handling (fstream) to ensure data is saved after the program closes.

 Technical Stack
Language: C++ (Standard 11 or higher)

Paradigm: Object-Oriented Programming (Classes, Inheritance, Encapsulation)

Storage: Flat files (.dat or .txt) for data management.

📁 Project Structure
Plaintext

├── main.cpp            # Entry point of the application
├── Hospital.h          # Header file containing class definitions
├── Hospital.cpp        # Implementation of core logic
├── data/
│   ├── patients.txt    # Database for patient records
│   └── doctors.txt     # Database for doctor records
└── README.md           # Project documentation
 Setup and Installation
Clone the Repository:

Bash

git clone https://github.com/yourusername/hospital-management-cpp.git
cd hospital-management-cpp
Compile the Code: Using G++ (MinGW):

Bash

g++ main.cpp Hospital.cpp -o HospitalSystem
Run the Application:

Bash

./HospitalSystem
 Usage
Upon launching the program, you will be greeted with a main menu:

Add New Patient: Enter name, age, gender, and blood group.

Search Doctor: Filter doctors by specialization (e.g., Cardiology, Pediatrics).

Book Appointment: Link a Patient ID with a Doctor ID and set a time.

Generate Bill: Calculate costs based on the doctor's fee and duration of stay.

Note: Ensure that the data/ folder exists in your directory, or the program will attempt to create it on the first run to store your files.

 Contributing
Contributions are welcome! If you'd like to improve the logic (e.g., adding a search algorithm or a GUI), please follow these steps:

Fork the project.

Create your Feature Branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.
