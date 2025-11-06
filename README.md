# 🚌 RouteMaster – Bus Scheduling & Booking System
## 🧩 A comprehensive platform streamlining bus transportation from booking to delivery.

---

## 🔗 Project Title: RouteMaster — Bus Transportation Management Platform
## 🧑‍💻 Role: Full-Stack Developer | System Designer
## 🖥️ Tech Stack: PHP, MySQL, HTML/CSS/JavaScript | XAMPP | Payment Gateway Integration

---

## ✨ Key Features:

### 🎫 **Passenger Portal**
- **User Registration & Authentication** – Secure signup and login system
- **Bus Search & Booking** – Search available buses by route, date, and time
- **Seat Reservation** – Real-time seat booking with instant confirmation
- **Payment Processing** – Integrated payment gateway supporting major cards and cryptocurrencies
- **Ticket Management** – View, print, and cancel tickets with digital receipts
- **Refund System** – Automated refund processing for cancelled bookings
- **Feedback System** – Submit and view feedback for service improvement

### 🚗 **Driver Portal**
- **Driver Dashboard** – Dedicated login and management interface
- **Route Management** – View assigned routes and schedules
- **Passenger Information** – Access passenger details for assigned trips
- **Real-time Updates** – Live schedule and route notifications

### 👨‍💼 **Admin Dashboard**
- **Comprehensive Management** – Complete system administration interface
- **Driver Management** – Add, edit, and manage driver information
- **Passenger Management** – View and manage passenger accounts
- **Bus Schedule Management** – Create and modify bus schedules
- **Feedback Management** – Monitor and respond to passenger feedback
- **System Analytics** – View booking statistics and performance reports

---

## 🛠️ Technology Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **Backend** | PHP |
| **Database** | MySQL (MariaDB) |
| **Server** | Apache/XAMPP |
| **Payment** | Stripe Integration |
| **UI/UX** | Responsive Design |

---

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

---

## 🗄️ Database Schema

The system uses a MySQL database (`busschedulings`) with the following main tables:

- **bus** – Bus schedules and routes
- **passenger** – Passenger account information
- **drivers** – Driver details and credentials
- **payment** – Payment transaction records
- **feedback** – Customer feedback and support tickets
- **createaccount** – User registration data

---

## 🚀 Installation & Setup

### Prerequisites
- XAMPP or similar local server environment
- PHP 8.2+ 
- MySQL/MariaDB
- Web browser

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/RouteMaster.git
   cd RouteMaster
   ```

2. **Setup Database**
   - Start XAMPP and ensure Apache and MySQL services are running
   - Open phpMyAdmin (http://localhost/phpmyadmin)
   - Create a new database named `busschedulings`
   - Import the `IWT_KDY/busschedulings.sql` file

3. **Configure Database Connection**
   - Edit `IWT_KDY/KNDUNI_20/config.php`
   - Update database credentials if needed:
     ```php
     $con = new mysqli("localhost", "root", "", "busschedulings");
     ```

4. **Access the Application**
   - Place the project in your XAMPP `htdocs` folder
   - Navigate to `http://localhost/RouteMaster/IWT_KDY/KNDUNI_20/`

---

## 💳 Payment Features

- **Multi-Payment Support** – Major credit/debit cards and cryptocurrencies
- **Secure Processing** – Encrypted payment gateway integration
- **Automated Refunds** – Instant refund processing for cancellations
- **Payment Confirmation** – Digital receipts and confirmation emails
- **Transaction History** – Complete payment record management

---

## 🔒 Security Features

- **Password Protection** – Secure user account management
- **Session Management** – Robust session handling and timeout
- **Input Validation** – Comprehensive data sanitization
- **SQL Injection Prevention** – Prepared statements and parameterized queries
- **Payment Security** – PCI-compliant payment processing

---

## 📱 User Interface

The application features a modern, responsive design with:
- **Clean Navigation** – Intuitive menu structure and user flow
- **Mobile-Friendly** – Responsive design for all device sizes
- **Professional Styling** – Modern CSS with smooth animations
- **Interactive Elements** – JavaScript-powered dynamic features

---

## 🛣️ Key Functionalities

1. **Real-time Bus Information** – Live updates on bus schedules and availability
2. **Instant Booking** – Quick and easy seat reservation process
3. **Payment Integration** – Multiple payment options for user convenience
4. **Ticket Management** – Digital ticket generation and management
5. **Refund Processing** – Automated refund system for cancellations
6. **Feedback System** – Customer support and feedback collection
7. **Admin Controls** – Comprehensive administrative tools

---

## 📞 Contact Information

- **Email**: userone@gmail.com
- **Phone**: +94 77 589 3213
- **Social Media**: RouteMaster/facebook.com

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🙏 Acknowledgments

- Built with modern web technologies
- Designed for scalability and maintainability
- Focused on user experience and accessibility
- Comprehensive error handling and validation

---

## 🚌 RouteMaster ensures transparency, security, and a seamless experience for every stakeholder — from passenger to driver to administrator!

**🔗 GitHub Repo**: https://github.com/yourusername/RouteMaster

**🙌 A big thanks to my amazing team for their collaboration, innovation, and hard work throughout this journey!**

#PHP #WebDevelopment #FullStackProject #BusSystem #MySQL #XAMPP #TeamWork #OnlineBooking #RouteMaster
