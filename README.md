# Relaxing Stay Hotels Management System

## Project Overview
This project models the Relaxing Stay Hotels management system using UML class and sequence diagrams. It showcases the following principles:
- **Composition and Inheritance**: Represented in the class diagram with relationships between Hotel, Manager, CleaningStaff, and FrontDeskStaff.
- **Encapsulation**: Applied in the design of operations assigned to service controllers.
- **Service Controllers**: Used to manage subsystems, such as employee management and room allocation.

## Technologies Used
- **Visual Paradigm**: For creating UML class and sequence diagrams.
- **Java** (Optional if you implemented any code).

## Case Study: Relaxing Stay Hotels
The hotel chain operates throughout Ontario and requires a system to manage employees and room bookings. The system is designed with the following scenarios:
1. **Generate Employee List**: Lists all employees and their respective roles.
2. **Hire Manager**: Adds a new manager and assigns them to a hotel.
3. **Create a Service Ticket**: Allows managers to assign cleaning staff to room service issues.
4. **Set Up New Hotel**: Adds a newly acquired hotel to the system.

## Class Diagram
The class diagram represents the hotel’s organizational structure and the relationships between employees and hotels.

![Class Diagram](![HotelManagementSystem](https://github.com/user-attachments/assets/695c7503-928f-4f7c-b2dc-dc2938a72b32)
)

## Sequence Diagrams
These diagrams illustrate the system interactions for key operations:

### Scenario 1: Generate Employee List
![Generate Employee List](![Create Employee List](https://github.com/user-attachments/assets/7b826c3d-70fd-4a56-b975-f39b7ff83f92))

### Scenario 2: Hire Manager
![Hire Manager](![Hire Manager](https://github.com/user-attachments/assets/2a26482a-0d7d-4261-b7f1-97ba9e318e32))

### Scenario 3: Create Service Ticket
![Create Service Ticket](![Generate Service ticket](https://github.com/user-attachments/assets/cd1bb31d-cc30-4e2e-9c1c-029d2c6801c0))

### Scenario 4: Set Up New Hotel
![Set Up New Hotel](![setup Hotel](https://github.com/user-attachments/assets/36d2acf5-8d51-42c5-9f48-7b0d420ac52c))

### Scenario 5: Payment System
![Payment System](![Payment](https://github.com/user-attachments/assets/26d21653-93c1-4d13-a829-bfdf484ee440))


## How the Project Was Done
1. **Class Diagram**: Developed based on the case study requirements using **composition** and **inheritance**. Each entity like Hotel, Manager, CleaningStaff, and FrontDeskStaff was designed with clear relationships.
   
2. **Sequence Diagrams**: For each scenario, a sequence diagram was created to represent the interaction between the user and the system. Service controllers were used to represent the interfaces that interact with subsystems like employee management and room setup.

3. **Operations**: Each message in the sequence diagrams represents an operation that is added to the respective classes, like `generateEmployeeList()` for the System or `hireManager()` for the OfficeAdministrator.

### Files in the Repository
- `hotel-management-system.vpp`: Visual Paradigm file containing all UML diagrams.
- PNG images of class and sequence diagrams for visualization.
