# Bus Reservation System

A simple bus reservation system developed using C++, featuring admin and user portals. The system allows users to book and cancel bus tickets, while admins can manage buses and view bookings. The data is stored using a file system, and the project incorporates exception handling for robustness.

## Description

- **Admin Portal**: Allows administrators to edit bus details and view bookings based on different filters. Admins can access the system using the credentials: `id = admin` and `password = pass`.
- **User Portal**: Enables users to book and cancel tickets. Every ticket is assigned a unique PNR, and the system tracks booking details such as time and date.
- **File System**: The application uses two `.dat` files:
  - `bus.dat`: Stores information about buses.
  - `ticket.dat`: Stores information about booked tickets.
- **Inheritance**: The system is built using two main classes:
  - `Bus Class`: Stores bus details.
  - `Ticket Class`: Inherits from the `Bus Class` and manages ticket-related details.
- **Random PNR Generation**: Every ticket is assigned a unique PNR using the `generatePNR` function.
- **Exception Handling**: The application incorporates exception handling where necessary to ensure smooth operation.

## Technology Used

- **Language**: C++
- **File Storage**: `.dat` files for storing bus and ticket data
- **Exception Handling**: Built-in C++ exception handling

## Running the Application

1. **Download and Extract**: Download the `.zip` folder and extract all files.
2. **Navigate to the Folder**: 
   Open the folder and copy its file path. Open a command prompt and navigate to the folder using the command:
   
   ```bash
   cd <filepath>
    ```

3.Run the Application: After navigating to the folder, type the following to run the program:
    ```bash
    main.exe
    ```

4.Admin Login: To access the admin portal, use the credentials:

    ID: admin
    Password: pass

# Usage

## User Portal
Users can book or cancel tickets.

## Admin Portal
Admins can add or edit buses and view bookings with filters.

## Date and Time
The `get_time` and `get_date` functions in the `utils` header retrieve the current date and time of a booking.

# Contributions
Feel free to fork this repository, make improvements, and submit a pull request. All contributions are welcome!

# Contact
If you have any questions or feedback, feel free to reach out:

Email: [gurijalahruday@gmail.com](mailto:gurijalahruday@gmail.com)
