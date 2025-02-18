# ParkEasy

ParkEasy is a web-based parking management system designed to streamline the process of booking and managing parking spaces. This project allows users to book parking slots in advance, view available spaces, and manage their reservations efficiently.

## Overview

This system provides an easy-to-use interface for users to check parking availability, book slots, and receive booking confirmations. It also includes an admin panel for managing parking slots, bookings, and user data.

## Features

- **User Registration & Login**: Users can register, log in, and manage their accounts securely.
- **Parking Slot Booking**: Users can view available parking spaces and book them in advance.
- **Interactive Map**: Displays parking locations for easy selection.
- **Booking Confirmation**: Users receive confirmation for their booked slots.
- **Booking History**: Users can review their past and upcoming bookings.
- **Admin Dashboard**: Admins can manage parking slots, view user bookings, and handle system settings.
- **Secure Database**: Stores user credentials, bookings, and parking slot information.
- **Responsive UI**: Designed using HTML, CSS, and JavaScript for an intuitive user experience.

## Tech Stack

- **Backend**: PHP for handling server-side operations and database interactions.
- **Frontend**: HTML, CSS, JavaScript for an interactive and responsive interface.
- **Database**: MySQL (SQL script available) for storing user, booking, and parking slot data.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/ParkEasy.git
   cd ParkEasy
   ```
2. **Set up the database:**
   - Import the provided SQL file into MySQL.
   - Update `config.php` with your database credentials.

3. **Run the application:**
   - Place the project files in the web server directory (e.g., `htdocs` for XAMPP).
   - Start Apache and MySQL using XAMPP or a similar tool.
   - Open `http://localhost/ParkEasy/` in your browser.

## Usage

1. **Register/Login**: Users create an account or log in to access the booking system.
2. **Book a Slot**: Users select a parking slot and confirm their reservation.
3. **View Bookings**: Users can check their current and past reservations.
4. **Admin Management**: Admins manage available slots, user bookings, and system settings.

## Database Structure

- **Users Table**: Stores user account details.
- **Parking Slots Table**: Stores available parking slot information.
- **Bookings Table**: Stores user reservations and booking details.

## Future Enhancements

- **Payment Integration**: Enable online payments for parking reservations.
- **Mobile App**: Develop a mobile-friendly version of ParkEasy.
- **Real-Time Availability**: Implement live updates for parking slot availability.

## Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the **MIT License**.

## Contact

For any issues or suggestions, please email `sanskrutishedge1005@gmail.com` or create an issue in the GitHub repository.
