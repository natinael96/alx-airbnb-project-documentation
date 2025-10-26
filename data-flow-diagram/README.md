# Airbnb Clone - Data Flow Diagram

## Overview
This directory contains the Data Flow Diagram (DFD) for the Airbnb Clone backend system, illustrating how data moves through the system from external entities through various processes to data stores and back.

## Files
- `airbnb-data-flow.drawio` - Draw.io source file for the DFD
- `data-flow.png` - Exported PNG image of the DFD
- `README.md` - This documentation file

## DFD Components

### External Entities
1. **Guest** - Users who search and book properties
2. **Host** - Users who list and manage properties
3. **Admin** - System administrators
4. **Payment Gateway** - External payment processing service
5. **Email Service** - External email notification service

### Data Stores
1. **User Database** - Stores user profiles and authentication data
2. **Property Database** - Stores property listings and details
3. **Booking Database** - Stores booking information and status
4. **Payment Database** - Stores transaction records and payment data
5. **Review Database** - Stores user reviews and ratings

### Processes
1. **Authentication Process (1.0)** - Handles user login and registration
2. **Property Management (2.0)** - Manages property listings
3. **Search & Filter Process (3.0)** - Handles property search and filtering
4. **Booking Process (4.0)** - Manages booking creation and management
5. **Payment Process (5.0)** - Handles payment processing
6. **Review & Rating Process (6.0)** - Manages reviews and ratings
7. **Notification Process (7.0)** - Handles email and in-app notifications
8. **Admin Management (8.0)** - System administration and monitoring

## Data Flow Summary

### Guest Data Flows
- Login/Registration → Authentication Process → User Database
- Search Criteria → Search Process → Property Database → Search Results
- Booking Request → Booking Process → Booking Database → Booking Confirmation
- Payment Data → Payment Process → Payment Gateway → Payment Receipt
- Review Data → Review Process → Review Database

### Host Data Flows
- Property Listing Data → Property Management → Property Database → Confirmation
- Booking Notifications ← Notification Process ← Booking Process

### Admin Data Flows
- Admin Commands → Admin Management → All Databases → System Reports

### System Data Flows
- Payment requests flow to external Payment Gateway
- Notification data flows to external Email Service
- All processes interact with appropriate data stores for persistence

## How to View the Diagram

1. Open `airbnb-data-flow.drawio` in Draw.io (https://app.diagrams.net/)
2. The diagram shows the complete data flow with labeled arrows indicating data movement
3. Export as PNG using File → Export as → PNG to create `data-flow.png`

## Key Features Illustrated

- **User Authentication Flow**: How users register, login, and manage profiles
- **Property Management Flow**: How hosts create and manage property listings
- **Search and Discovery Flow**: How guests find and filter properties
- **Booking Process Flow**: Complete booking lifecycle from search to confirmation
- **Payment Integration Flow**: How payments are processed through external gateways
- **Review System Flow**: How reviews are created and stored
- **Notification Flow**: How system notifications are generated and sent
- **Admin Management Flow**: How administrators monitor and manage the system

This DFD provides a comprehensive view of all data movements within the Airbnb Clone system, making it easier to understand system architecture and data dependencies.
