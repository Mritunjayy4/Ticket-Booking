# Ticket Booking Backend System

A Java-based console application designed to simulate and manage the ticket booking workflow for a train reservation system. This project demonstrates backend service design fundamentals, focusing on object-oriented programming, data handling, and scalable architecture.

## Features

- **User Management:**  
  - Registration and authentication  
  - User-specific ticket management and booking history  

- **Train Management:**  
  - Define routes, schedules, and available trains  
  - Dynamic seat allocation and status tracking  

- **Ticket Booking Workflow:**  
  - Book, view, and cancel tickets  
  - Real-time seat availability and error handling  
  - Persist user, train, and booking data using file-based simulation  

- **Command-Line Interface:**  
  - Intuitive console-driven interaction for performing all major operations  
  - Modular codebase for easy extensibility and maintenance  

## Technologies Used

- Java (Core, Collections, OOP Principles)
- File I/O for data persistence
- Modular service and entity class design
- Command-line based UI

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/singhdevhub-lovepreet/ticketBooking.git
    cd ticketBooking
    ```

2. **Compile the source code:**
    ```bash
    javac -d bin src/*.java
    ```

3. **Run the application:**
    ```bash
    java -cp bin Main
    ```

## Project Structure

- `src/`: Source files and modular Java classes (User, Train, Ticket, Service classes, Utils)
- `bin/`: Compiled Java classes
- `data/`: (If present) Simulated database files for persistence

