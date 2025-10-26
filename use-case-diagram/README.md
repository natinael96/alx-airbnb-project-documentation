# Use Case Diagram for Airbnb Project

This directory contains the use case diagram for the Airbnb project, visualizing the interactions between users and the system for key functionalities.

## Diagram Contents

The use case diagram includes the following key actors and interactions:

### Actors
- **Guest** - Users who search for and book properties
- **Host** - Property owners who list and manage their properties
- **Admin** - System administrators who manage the platform

### Key Use Cases
1. **User Registration & Authentication**
   - Register as Guest
   - Register as Host
   - Login
   - Logout
   - Reset Password

2. **Property Management (Host)**
   - Create Property Listing
   - Update Property Details
   - Manage Availability
   - View Booking Requests
   - Accept/Decline Bookings
   - Manage Reviews

3. **Property Search & Booking (Guest)**
   - Search Properties
   - Filter Search Results
   - View Property Details
   - Book Property
   - Cancel Booking
   - Leave Review

4. **Payment Processing**
   - Process Payment
   - Refund Payment
   - View Payment History
   - Manage Payment Methods

5. **Communication**
   - Send Message to Host
   - Send Message to Guest
   - View Messages

6. **Admin Functions**
   - Manage Users
   - Moderate Content
   - Handle Disputes
   - View Analytics

## File Structure
- `airbnb-use-case-diagram.png` - The main use case diagram exported from Draw.io
- `airbnb-use-case-diagram.drawio` - The Draw.io source file (optional)

## Instructions for Creating the Diagram

1. Open [Draw.io](https://app.diagrams.net/)
2. Create a new diagram
3. Use the following elements:
   - **Actors**: Use stick figure symbols for Guest, Host, and Admin
   - **Use Cases**: Use oval shapes for each functionality
   - **System Boundary**: Use a rectangle to represent the Airbnb system
   - **Relationships**: Use arrows to show interactions between actors and use cases

4. Export the diagram as PNG format
5. Save the file as `airbnb-use-case-diagram.png` in this directory

## Key Relationships to Include

- Guest interactions with booking, search, and payment use cases
- Host interactions with property management and communication use cases
- Admin interactions with user management and system oversight use cases
- Include relationships between use cases where applicable (e.g., "Book Property" includes "Process Payment")
