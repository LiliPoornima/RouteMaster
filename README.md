# RouteMaster
# RouteMaster - Bus Scheduling and Booking System

## 📋 Project Overview

RouteMaster is a comprehensive web-based bus scheduling and booking system that provides real-time bus information, seat reservation, and payment processing. The system serves as a complete solution for bus transportation management with separate interfaces for passengers, drivers, and administrators.

## 🚀 Features

### For Passengers
- **User Registration & Authentication**: Secure signup and login system
- **Bus Search & Booking**: Search available buses by route, date, and time
- **Seat Reservation**: Real-time seat booking with instant confirmation
- **Payment Processing**: Secure payment gateway supporting major cards and cryptocurrencies
- **Ticket Management**: View, print, and cancel tickets
- **Refund System**: Automated refund processing for cancelled bookings
- **Feedback System**: Submit and view feedback for service improvement

### For Drivers
- **Driver Portal**: Dedicated login and dashboard for drivers
- **Route Management**: View assigned routes and schedules
- **Passenger Information**: Access passenger details for assigned trips

### For Administrators
- **Admin Dashboard**: Comprehensive management interface
- **Driver Management**: Add, edit, and manage driver information
- **Passenger Management**: View and manage passenger accounts
- **Bus Schedule Management**: Create and modify bus schedules
- **Feedback Management**: Monitor and respond to passenger feedback
- **System Analytics**: View booking statistics and reports

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: PHP
- **Database**: MySQL (MariaDB)
- **Server**: Apache/XAMPP
- **Payment Integration**: Support for major payment gateways

## 📁 Project Structure

```
RouteMaster/
├── IWT_KDY/
│   ├── busschedulings.sql          # Database schema and sample data
│   └── KNDUNI_20/                 # Main application directory
│       ├── Homepage.php           # Landing page
│       ├── config.php             # Database configuration
│       ├── admindash.php          # Admin dashboard
│       ├── passengerLogIn.php     # Passenger login
│       ├── passregisteration.php  # Passenger registration
│       ├── driverlogin.php        # Driver login
│       ├── reserve.php            # Bus reservation system
│       ├── payment.php            # Payment processing
│       ├── feedback.php           # Feedback system
│       └── *.css                  # Stylesheet files
└── README.md
```

## 🗄️ Database Schema

The system uses a MySQL database (`busschedulings`) with the following main tables:

- **bus**: Bus schedules and routes
- **passenger**: Passenger account information
- **drivers**: Driver details and credentials
- **payment**: Payment transaction records
- **feedback**: Customer feedback and support tickets
- **createaccount**: User registration data

## 🚀 Installation & Setup

### Prerequisites
- XAMPP or similar local server environment
- PHP 8.2+ 
- MySQL/MariaDB
- Web browser

## 👥 User Roles

### Passenger
- Register and create account
- Search and book bus tickets
- Make payments and manage bookings
- Submit feedback and support requests

### Driver
- Login to driver portal
- View assigned routes and schedules
- Access passenger information for trips

### Administrator
- Manage all system operations
- Add/edit drivers and bus schedules
- Monitor bookings and payments
- Handle customer feedback

## 💳 Payment Features

- Support for major credit/debit cards
- Cryptocurrency payment options
- Secure payment processing
- Automated refund system
- Payment confirmation and receipts

## 🔒 Security Features

- Password-protected user accounts
- Secure payment processing
- Session management
- Input validation and sanitization
- SQL injection prevention

## 📱 User Interface

The application features a modern, responsive design with:
- Clean and intuitive navigation
- Mobile-friendly interface
- Professional styling with CSS
- Interactive elements with JavaScript

## 🛣️ Key Functionalities

1. **Real-time Bus Information**: Live updates on bus schedules and availability
2. **Instant Booking**: Quick and easy seat reservation process
3. **Payment Integration**: Multiple payment options for user convenience
4. **Ticket Management**: Digital ticket generation and management
5. **Refund Processing**: Automated refund system for cancellations
6. **Feedback System**: Customer support and feedback collection
7. **Admin Controls**: Comprehensive administrative tools



## 🙏 Acknowledgments

- Built with modern web technologies
- Designed for scalability and maintainability
- Focused on user experience and accessibility
- Comprehensive error handling and validation

---

**RouteMaster** - Making bus travel simple, secure, and convenient! 🚌✨
