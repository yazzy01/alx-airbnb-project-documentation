# Instructions for Creating the AirBnB Clone Data Flow Diagram

Use Draw.io or a similar tool to create a comprehensive Data Flow Diagram (DFD) for the AirBnB Clone system following these instructions.

## Diagram Elements

### External Entities (Use rectangles)
- **Guest**: Regular user looking to book properties
- **Host**: User who lists and manages properties
- **Admin**: System administrator
- **Payment Gateway**: External payment processing system
- **Email Service**: External notification system
- **Map Service**: External location and mapping service

### Processes (Use circles/ovals)
Include the following key processes:
1. **User Registration & Authentication**
2. **Property Listing Management**
3. **Search & Filter**
4. **Booking Management**
5. **Payment Processing**
6. **Review & Rating Management**
7. **Notification Management**
8. **Administrative Controls**

### Data Stores (Use open-ended rectangles or database symbols)
- **Users DB**: Stores user account information
- **Properties DB**: Stores property listing details
- **Bookings DB**: Stores booking information
- **Payments DB**: Stores payment records
- **Reviews DB**: Stores user reviews and ratings
- **Messages DB**: Stores communication between users
- **System Logs**: Stores system activity records

### Data Flows (Use arrows)
Draw arrows to show the flow of data between entities, processes, and data stores.
Label each arrow with the type of data being transmitted.

## DFD Structure

### Level 0 DFD (Context Diagram)
Show the system as a single process interacting with all external entities.

### Level 1 DFD
Expand the single process into the main processes and show:
- How data flows between processes
- How processes interact with data stores
- How external entities connect to specific processes

## Export Requirements
- Create using Draw.io (or similar DFD tool)
- Use standard DFD notation
- Export as PNG file with resolution of at least 1920x1080
- Name the file "data-flow.png"
- Place in this directory 