# Airline Reservation and Management System

A console-based **Airline Reservation and Management System** developed in **C++** using **Object-Oriented Programming (OOP)** and Modern C++ features.

The system simulates the main operations of an airline, supporting different user roles and providing functionality for flight management, reservations, passenger management, check-in, aircraft maintenance, and reporting.

## Project Overview

The system supports three main user roles:

- **Administrator**
- **Booking Agent**
- **Passenger**

Each role has access to different functionalities through a role-based authentication system.

## Key Features

### Administrator

- User account management
- Flight scheduling and management
- Aircraft management
- Crew assignment
- Flight status management
- Operational reports
- Maintenance reports
- User activity reports

### Booking Agent

- Search for available flights
- Create reservations
- Select seats
- Modify reservations
- Cancel reservations
- Simulated payment processing
- Refund processing
- Airport check-in assistance

### Passenger

- Search for available flights
- Book flights
- Select seats
- View reservations
- Online check-in
- Generate boarding passes
- Manage passenger information
- Loyalty program support

## Flight Management

The system manages flight information including:

- Flight number
- Origin and destination
- Departure and arrival date/time
- Aircraft type
- Flight status
- Available seats

It also supports flight searching and filtering based on different criteria.

## Aircraft & Crew Management

The system maintains aircraft information, including:

- Aircraft specifications
- Availability
- Maintenance schedules
- Maintenance logs

Administrators can also assign pilots and flight attendants to flights.

## Reservation System

The reservation module supports:

- Flight searching
- Seat selection
- Reservation creation
- Reservation modification
- Reservation cancellation
- Booking confirmation
- Waitlist support
- Simulated payments
- Refund handling

## Check-In & Boarding

Passengers can check in online and obtain a boarding pass.

The system also supports airport check-in operations and boarding procedures.

## Maintenance Tracking

Aircraft maintenance can be tracked through:

- Scheduled maintenance
- Maintenance history
- Parts replaced
- Issues encountered
- Aircraft availability

## Reporting

The system provides reports related to:

- Flight performance
- Reservations
- Financial summaries
- Maintenance activities
- Aircraft utilization
- User activities

## Data Persistence

The project uses **file-based data storage** for persistent information.

Data is stored using files such as:

- CSV files
- Text files

## Technical Concepts

The project applies several C++ and OOP concepts:

- Classes and Objects
- Encapsulation
- Inheritance
- Polymorphism
- Smart Pointers
- STL Containers
- Lambda Expressions
- Exception Handling
- Input Validation
- File Handling
- C++17 `<filesystem>`

## Technologies

- **C++**
- **C++17**
- **Object-Oriented Programming**
- **STL**
- **Git / GitHub**
- **Makefile**
- **CSV / File-based persistence**

## Project Structure

```text
Airline-Reservation-and-Management-System/
│
├── README.md
│
└── Source/
    │
    ├── database/
    │   ├── Aircraft.csv
    │   ├── Flights.csv
    │   ├── Maintenance.csv
    │   ├── Passengers.csv
    │   ├── Payments.csv
    │   ├── Reservations.csv
    │   ├── Users.csv
    │   └── flight_crew.csv
    │
    ├── docs/
    │   ├── BRD.txt
    │   ├── SWS.txt
    │   ├── UML.puml
    │   └── image.png
    │
    ├── include/
    │   └── Header Files
    │
    ├── src/
    │   └── Source Files
    │
    └── Makefile
```

## Build & Run

Navigate to the `Source` directory:

```bash
cd Source
```

Build the project:

```bash
make build
```

Run the application:

```bash
make run
```

## Project Documentation

The `docs` directory contains project documentation, including:

- **BRD** – Business Requirements Document
- **SWS** – Software Specification
- **UML** – Class diagram
- Project documentation materials

## Project Objective

The objective of this project is to simulate the comprehensive operations of an airline reservation and management system while applying **Object-Oriented Programming principles and Modern C++ features** in a practical software project.
