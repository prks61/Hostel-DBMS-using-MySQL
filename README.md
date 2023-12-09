# Hostel Management System

This is a Hostel Management System built with PHP and MySQL. It provides a simple interface for managing hostel bookings, rooms, and user profiles.

## Project Structure

The project is structured into two main directories: the root directory and the `admin` directory. The root directory contains files for the user-facing side of the application, while the `admin` directory contains files for the admin side.

### User Side

- [`book-hostel.php`](hostel/book-hostel.php): This file handles the booking of hostels.
- [`hostel.css`](hostel/hostel.css): This file contains the CSS styles for the user side of the application.
- [`my-profile.php`](hostel/my-profile.php): This file displays the profile of the logged-in user.
- [`login.php`](hostel/login.php): This file handles user login.

### Admin Side

- [`admin-profile.php`](hostel/admin/admin-profile.php): This file displays the profile of the logged-in admin.
- [`create-room.php`](hostel/admin/create-room.php): This file handles the creation of new rooms.
- [`dashboard.php`](hostel/admin/dashboard.php): This file displays the admin dashboard.

## Database

The [`hostel.sql`](hostel.sql) file contains the SQL commands to create the database and tables needed for this application.

## Setup

To set up this project, you need to have PHP and MySQL installed on your machine. After that, you can clone this repository and import the `hostel.sql` file into your MySQL database.

## Usage

To use this application, start your PHP server and open the `index.php` file in your web browser. You can then register a new user or log in as an existing user. If you want to access the admin side, you need to log in as an admin.

## Contributing

Contributions are welcome. Please open an issue or submit a pull request if you have something to add.

## License

This project is licensed under the MIT License.