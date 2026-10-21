# Hospital-Management-System
Java Swing-based Hospital Management System with patient records, doctor and staff management, pharmacy stock, room allocation, billing, attendance, and reports.

# Hospital Management System

A Java-based desktop application developed to demonstrate the basic operations of a hospital management system. The application provides a centralized interface for managing hospital records and administrative activities using Java Swing, AWT, and Core Java.

## Overview

The Hospital Management System is an academic Project-Based Learning (PBL) project developed for the **CS25C09 – Java Programming** course.

It is designed for authorized hospital personnel to manage patient records, doctors, staff, medicine stock, room and bed allocation, billing, attendance, and reports through a desktop interface.

**This project is a prototype that uses in-memory demo data. It does not use a live database.**

## Features

- **Login System** – Access the application through a login screen.
- **Dashboard** – View hospital summary information and navigate between modules.
- **Patient Management** – Add, update, delete, search, and view patient records.
- **Doctor Management** – Manage doctor information.
- **Staff Management** – Maintain hospital staff records.
- **Pharmacy Management** – Manage medicine details, stock in/out, and low-stock information.
- **Room and Bed Management** – View room and bed details and manage bed allocation and release.
- **Billing Management** – Generate and manage sample hospital bills.
- **Attendance Management** – Maintain staff attendance records.
- **Reports** – View summary information from the application.

## Technology Stack

- **Language:** Java
- **GUI:** Java Swing and AWT
- **Programming Concepts:** Object-Oriented Programming (OOP), classes, objects, inheritance, encapsulation, and event handling
- **Data Storage:** Java objects and ArrayList (in-memory demo data)
- **IDE:** Visual Studio Code

## Project Structure

The project is organized into separate Java files for data models, application data, login, dashboard, and individual management modules.

Key files include:

- `Main.java` – Application entry point
- `LoginFrame.java` – Login interface
- `DashboardFrame.java` – Main dashboard
- `HospitalData.java` – In-memory application data
- `Patient.java`, `Doctor.java`, `Staff.java` – Entity classes
- `PatientManagementFrame.java` – Patient management interface
- `PharmacyFrame.java` – Pharmacy and stock management
- `RoomBedFrame.java` – Room and bed management
- `BillingFrame.java` – Billing interface
- `AttendanceFrame.java` – Attendance interface
- `ReportsFrame.java` – Summary reports

## How to Run

### Prerequisites
- Java Development Kit (JDK) installed
- Visual Studio Code or another Java-compatible IDE

### Steps

1. Clone or download this repository.
2. Open the project folder in your terminal.
3. Compile the Java files:

   ```bash
   javac *.java
   ```

4. Run the application:

   ```bash
   java Main
   ```

## Demo Login

- **Username:** `admin`
- **Password:** `admin123`

Use these credentials only for the academic demonstration.

## Data and Limitations

- The application uses fictional sample records for demonstration.
- Data is stored in memory using Java objects and ArrayList.
- Records are not permanently saved and reset when the application restarts.
- This prototype is not intended for real hospital operations or real patient data.
- MySQL and JDBC are not used in the current implementation.

## Future Enhancements

- Integrate MySQL using JDBC for persistent storage.
- Add role-based access control.
- Implement data backup and restore.
- Expand reporting and analytics.
- Support multi-user access with appropriate backend and security controls.

## Academic Information

- **Course:** CS25C09 – Java Programming
- **Project:** Hospital Management System
- **Department:** Artificial Intelligence and Data Science
- **Institution:** SRM Madurai College for Engineering and Technology
- **Academic Year:** 2026–2027

## Team

This project was developed as a team-based academic PBL activity. Team member responsibilities include module development, project coordination, integration, testing, documentation, and presentation.

---

*Developed as a Java Programming academic project to practise object-oriented programming, GUI development, and modular application design.*
