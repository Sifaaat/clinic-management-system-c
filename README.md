# 🏥 Clinic Appointment Scheduling System (C)


## A menu-driven Hospital / Clinic Appointment Management System developed in C language using file handling.
This project is designed as a capstone / academic project, demonstrating core software engineering concepts such as data persistence, role-based access, and modular programming.

📌 Features
🔐 Admin Module

Register new patients

Add doctors with specialty and available time

View all patients

View all doctors

View all appointments

Search patient by ID

Search doctor by specialty

Delete patient (automatically removes related appointments)

Delete doctor (automatically removes related appointments)

Delete appointments

👤 Patient Module (No Login Required)

View doctors

Search doctor by specialty

Book appointments

View own appointments

⏱ Appointment Handling

Prevents double booking for the same doctor and time slot

Stores appointment data persistently using files

🛠 Technologies Used

Programming Language: C

Concepts:

File Handling (.txt files)

Structures (struct)

Modular Functions

Menu-driven Interface

Input Validation

Storage: Text files (CSV-style)

## 📂 Project Structure


Clinic-Appointment-System/
│
├── main.c
├── data/
│   ├── patients.txt
│   ├── doctors.txt
│   ├── appointments.txt
│
└── README.md


The data directory is automatically created when the program runs.

▶️ How to Run
🔹 Compile
gcc main.c -o clinic

🔹 Run
./clinic


(On Windows, run clinic.exe)

🔑 Admin Access

Admin Password: admin123

⚠️ Note: The admin password is hardcoded for academic purposes only.

📄 File Format Details
patients.txt
patientID,name,age

doctors.txt
doctorID,name,specialty,availableTime

appointments.txt
doctorID,patientID,time

🚀 Future Improvements

Patient authentication system

Fixed appointment time slots

Appointment cancellation by patient

Binary file storage (.dat)

Doctor-wise appointment reports

🎓 Academic Purpose

This project was developed as part of a university capstone / coursework to demonstrate:

Problem-solving using C

Persistent data management

Role-based system design

Real-world clinic workflow simulation

👨‍💻 Author

Sifat
BSc in Software Engineering

📜 License

This project is for educational use only.
