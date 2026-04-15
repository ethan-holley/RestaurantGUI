# Restaurant Ordering System (Java)

## Overview
A desktop application that simulates a restaurant ordering system from a server and manager perspective. The application allows staff to manage tables, process orders, and track billing and revenue in a structured and interactive environment.

Built using Java and Swing, the project follows the Model-View-Controller (MVC) design pattern to ensure separation of concerns and scalability.

---

## Features
- User authentication (server and manager roles)
- Table management and seating workflow
- Order creation and bill generation
- Payment processing and tip tracking
- Manager dashboard for revenue and item analytics
- Sorting of menu items by frequency and revenue

---

## Tech Stack
- Java
- Java Swing (GUI)
- Object-Oriented Programming (OOP)
- MVC Architecture

---

## System Design

### Architecture
The application is structured using the **Model-View-Controller (MVC)** pattern:
- **Model**: Handles data, business logic, and state management  
- **View**: GUI components built with Swing  
- **Controller**: Manages user input and system interactions  

---

### Data Structures & Design Decisions
- **HashMaps**
  - UserDatabase: maps usernames → User objects for efficient authentication  
  - Menu: maps menu items → prices for fast order processing  
  - Bill: maps items → costs for quick aggregation  
  - Server: maps tables → lists of bills for tracking active orders  

- **ArrayLists**
  - Used for collections where iteration is more important than lookup (e.g., closed tabs)

- **Enums**
  - Used for tables and security questions to avoid primitive overuse and improve type safety  

---

### Interfaces & Abstraction
- Implemented the `Comparator` interface to support:
  - Sorting menu items by frequency  
  - Sorting by revenue contribution  

---

### Encapsulation
- All internal data structures are protected through:
  - Unmodifiable views or deep copies when returned  
  - Prevention of external mutation (no escaping references)  

Example:
- User objects are returned as copies to preserve immutability  
- Bill lists are returned as copied collections  

---

## How to Run
1. Open the project in your IDE  
2. Run the `LoginFrame` class (contains the main method)  
3. Create an account or log in as a user  

### Manager Login (Demo Access)
- Username: `management`  
- Password: `Manager!123`  

---

## Notes
This project demonstrates strong use of object-oriented design principles, data structure selection, and separation of concerns in a real-world simulation scenario.
