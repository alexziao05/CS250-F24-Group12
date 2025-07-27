# BeAvis Car Rental System

**CS250 Fall 2024 - Group 12**

A modern, secure car rental management system designed to replace outdated rental processes with a comprehensive mobile app and web platform.

## Team Members

- **Abdihakim Ahmed**
- **Jake Foster** 
- **Alex Huang** (@alexziao05)

## Project Overview

The BeAvis Car Rental System is a full-stack application that modernizes car rental operations through:

- **Multi-platform Access**: Available as a mobile app (iOS/Android) and web application
- **Secure Authentication**: Two-factor authentication and identity verification
- **Location-based Services**: GPS integration for finding nearby vehicles
- **Secure Payment Processing**: PCI DSS compliant payment system with bank API integration
- **Real-time Inventory Management**: Live vehicle availability tracking
- **Manager Portal**: Administrative dashboard for fleet and customer management

## System Architecture

### Technology Stack
- **Database**: SQL (primary) with NoSQL caching (Redis)
- **Architecture**: Microservices with API Gateway
- **Payment**: PCI DSS compliant with bank API integration
- **Location Services**: GPS/satellite integration with load balancing
- **Security**: Separated databases for enhanced data protection

### Key Components
- **User Management**: Secure account creation and authentication
- **Vehicle Management**: Real-time inventory and availability tracking
- **Payment Processing**: Secure, encrypted transaction handling
- **Location Services**: GPS-enabled vehicle and customer location tracking
- **Manager Portal**: Administrative controls and analytics

## Planned Features

### Customer Features
- 📋 Account registration with email verification
- 📋 Two-factor authentication for secure login
- 📋 Location-based vehicle search
- 📋 Real-time vehicle availability
- 📋 Secure payment processing
- 📋 Rental history and payment tracking
- 📋 Reservation management (create/cancel)
- 📋 GPS-enabled closest vehicle finder

### Employee Features
- 📋 Inventory management and updates
- 📋 Reservation processing and returns
- 📋 Vehicle availability updates
- 📋 Fleet status monitoring
- 📋 Customer rental history access

### Manager Features
- 📋 Comprehensive analytics dashboard
- 📋 Fleet management across all locations
- 📋 Customer data and rental history
- 📋 Financial reporting and transaction monitoring

## Database Schema Design

### Proposed Core Tables
- **Customer**: User profiles, contact info, payment methods
- **Vehicle**: Fleet inventory with detailed specifications
- **Rental Transaction**: Payment records and booking history
- **Location Services**: GPS coordinates and vehicle positioning

## Proposed Security Features

- **Data Separation**: Isolated databases for different data types
- **PCI DSS Compliance**: Secure payment card industry standards
- **Two-Factor Authentication**: Enhanced login security
- **Encrypted Storage**: Secure handling of sensitive PII
- **API Gateway**: Centralized security and request management

## Development Timeline

| Phase | Duration | Focus |
|-------|----------|-------|
| **Phase 1** | 2-3 weeks | Planning, requirements, team roles |
| **Phase 2** | 3-4 weeks | UI/UX design and user experience |
| **Phase 3** | 8 weeks | Backend development and database setup |
| **Phase 4** | 4-6 weeks | Frontend development and API integration |
| **Phase 5** | 2-4 weeks | Testing, QA, and security validation |
| **Phase 6** | 1 week | Launch preparation and maintenance setup |

## Proposed Testing Strategy

### Planned Unit Testing
- Individual component functionality (getters/setters, authentication)
- Database operations and data validation
- Payment processing components

### Planned Integration Testing
- Multi-class interactions (reservations, payments)
- API endpoint testing
- Database connectivity and transactions

### Planned System Testing
- End-to-end user workflows
- Error handling and edge cases
- Security and performance validation

## Documentation

- [`UML Diagram.xml`](UML%20Diagram.xml) - Complete class structure and relationships
- [`Architectual Diagram.xml`](Architectual%20Diagram.xml) - System architecture and data flow
- [`BeAvis Car Rental System (1).pdf`](BeAvis%20Car%20Rental%20System%20(1).pdf) - Full project specifications
- [`Group Contract.txt`](Group%20Contract.txt) - Team collaboration guidelines

## Designed Class Structure

### Planned Core Classes
- **Platform**: Central system coordinator with database operations
- **UserAccount**: Base class for all user types with authentication
- **CustomerAccount**: Customer-specific features and rental history
- **EmployeeAccount**: Administrative functions and inventory management
- **Car**: Vehicle information and specifications
- **Location**: Geographic data and vehicle positioning
- **Payment**: Transaction processing and financial operations
- **Card**: Secure payment method storage

## Getting Started

> **Note**: This project is currently in the design and planning phase. Implementation has not yet begun.

### Future Prerequisites
```bash
# Database setup (SQL + Redis)
# Mobile development environment (iOS/Android)
# Web development stack
# Payment gateway API access
# GPS/mapping services API
```

### Future Installation
```bash
# Clone the repository
git clone https://github.com/alexziao05/CS250-F24-Group12.git

# Navigate to project directory
cd CS250-F24-Group12

# Install dependencies
# (Commands will be added during implementation phase)
```

## Contributing

Our team follows established protocols from our group contract:
- **Decision Making**: Democratic voting system for technical approaches
- **Communication**: Regular Discord updates and bi-weekly meetings
- **Code Review**: Collaborative review process before integration
- **Quality Assurance**: Comprehensive testing before deployment

## Communication

- **Platform**: Discord group chat
- **Meetings**: Tuesdays and Thursdays (evenings)
- **Deadlines**: Internal deadline 2 days before official due dates
- **Documentation**: Maintained in shared repository

## License

Educational project developed for CS250 Software Engineering course.

---

*Last Updated: July 26, 2025*  
*Status: Design and Planning Phase - Implementation Not Yet Started*
