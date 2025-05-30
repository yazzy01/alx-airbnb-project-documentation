# Instructions for Creating the AirBnB Clone Use Case Diagram

Use Draw.io or a similar tool to create a comprehensive Use Case Diagram for the AirBnB Clone system following these instructions.

## Diagram Elements

### Actors (Use stick figures)
- **Guest**: Regular user looking to book properties
- **Host**: User who lists and manages properties
- **Admin**: System administrator
- **External Systems**:
  - Payment Gateway (e.g., Stripe, PayPal)
  - Email Service
  - Map Service

### Use Cases (Use ovals)
Include the following key use cases from the README.md file:
- User Management use cases (Register, Login, etc.)
- Property Management use cases (Create Listing, Edit Listing, etc.)
- Search and Booking use cases (Search Properties, Make Booking, etc.)
- Payment Processing use cases (Process Payment, Issue Refund, etc.)
- Reviews and Ratings use cases (Leave Review, Respond to Review, etc.)
- Administrative use cases (Manage Users, Moderate Content, etc.)

### Relationships (Use lines)
- **Association**: Connect actors to the use cases they interact with (solid line)
- **Include**: Show when one use case includes another (dashed arrow with «include»)
- **Extend**: Show when one use case extends another (dashed arrow with «extend»)
- **Generalization**: Show when one actor or use case specializes another (solid line with hollow arrow)

## Design Guidelines

### Layout
- Place actors around the outside of the diagram
- Group related use cases together
- Use a system boundary box (rectangle) to enclose all use cases

### Color Coding (Optional)
- Different colors for different categories of use cases
- Different colors for different actors

### Labels
- Use clear, concise names for all elements
- Use consistent naming convention (verb + noun for use cases)

## Technical Requirements

- Create using Draw.io (or similar UML diagramming tool)
- Export as PNG file with resolution of at least 1920x1080
- Name the file "AirBnB_UseCase_Diagram.png"
- Place in the use-case-diagram directory

## Additional Notes

- Keep the diagram clean and readable
- Focus on showing the system's functionality from the users' perspective
- Include all major interactions but avoid excessive detail
- Follow standard UML notation for use case diagrams
