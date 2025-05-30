# AirBnB Clone: Use Case Diagram

This document explains the Use Case Diagram for the AirBnB Clone backend system. The diagram visualizes how different actors (users) interact with the system's core functionalities.

## Overview

The Use Case Diagram illustrates the interactions between users and the AirBnB Clone system. It shows the various actions that different types of users (Guest, Host, and Admin) can perform within the system.

![AirBnB Clone Use Case Diagram](./AirBnB_UseCase_Diagram.png)

## Actors

### 1. Guest
A regular user who is looking to book properties for temporary stays. Guests can browse listings, make bookings, leave reviews, etc.

### 2. Host
A user who owns or manages properties available for rental. Hosts can create and manage property listings, accept bookings, receive payments, etc.

### 3. Admin
A system administrator with elevated privileges who manages the platform, moderates content, and handles user issues.

### 4. External Systems
- **Payment Gateway**: External system for processing payments (e.g., Stripe, PayPal)
- **Email Service**: External system for sending notifications and alerts
- **Map Service**: External system for location-based features

## Key Use Cases

### User Management

1. **Register Account**
   - Actors: Guest, Host
   - Description: New users can create an account with the system

2. **Login/Authenticate**
   - Actors: Guest, Host, Admin
   - Description: Existing users can authenticate themselves to access the system

3. **Manage Profile**
   - Actors: Guest, Host, Admin
   - Description: Users can update their personal information, preferences, and settings

4. **Verify Identity**
   - Actors: Guest, Host
   - Description: Users can verify their identity to build trust on the platform

### Property Management

5. **Create Property Listing**
   - Actors: Host
   - Description: Hosts can create new property listings with details, photos, pricing, etc.

6. **Edit/Update Listing**
   - Actors: Host
   - Description: Hosts can modify property information, availability, and pricing

7. **Delete Listing**
   - Actors: Host, Admin
   - Description: Hosts can remove their listings; Admins can remove inappropriate listings

8. **Manage Availability Calendar**
   - Actors: Host
   - Description: Hosts can set and update the availability dates for their properties

### Search and Booking

9. **Search Properties**
   - Actors: Guest
   - Description: Guests can search for properties based on location, dates, price, etc.

10. **Filter Search Results**
    - Actors: Guest
    - Description: Guests can apply filters to refine search results

11. **View Property Details**
    - Actors: Guest
    - Description: Guests can view detailed information about a property

12. **Make Booking Request**
    - Actors: Guest
    - Description: Guests can request to book a property for specific dates

13. **Confirm/Reject Booking**
    - Actors: Host
    - Description: Hosts can approve or decline booking requests

14. **Cancel Booking**
    - Actors: Guest, Host
    - Description: Both guests and hosts can cancel bookings (subject to policies)

### Payment Processing

15. **Process Payment**
    - Actors: Guest, Payment Gateway
    - Description: Guests make payments for bookings through a secure payment gateway

16. **Issue Refund**
    - Actors: Admin, Payment Gateway
    - Description: Admins can process refunds for cancellations or disputes

17. **Receive Payout**
    - Actors: Host, Payment Gateway
    - Description: Hosts receive payments for completed stays

### Reviews and Ratings

18. **Leave Review**
    - Actors: Guest
    - Description: Guests can leave ratings and reviews for properties they've stayed at

19. **Respond to Review**
    - Actors: Host
    - Description: Hosts can respond to guest reviews

20. **Moderate Review**
    - Actors: Admin
    - Description: Admins can remove inappropriate reviews

### Administrative Functions

21. **Manage Users**
    - Actors: Admin
    - Description: Admins can manage user accounts, suspend users, etc.

22. **Moderate Content**
    - Actors: Admin
    - Description: Admins can review and moderate user-generated content

23. **Generate Reports**
    - Actors: Admin
    - Description: Admins can generate system usage and performance reports

## Relationships

- **Include Relationships**: Indicate that one use case includes the functionality of another use case
- **Extend Relationships**: Indicate optional behavior that may be triggered under certain conditions
- **Generalization Relationships**: Indicate that one use case is a specialized form of another

## Design Notes

The Use Case Diagram has been designed to:
- Clearly show the main functionalities of the system
- Distinguish between different user roles and their capabilities
- Show interactions with external systems
- Maintain readability while being comprehensive

## Technical Format

The diagram was created using Draw.io and exported as a PNG file. It follows standard UML (Unified Modeling Language) conventions for use case diagrams.
