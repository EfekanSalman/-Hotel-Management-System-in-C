# Hotel Management System in C

This is a simple hotel management system written in C. It allows hotel staff to manage guest check-ins, check-outs, and room bookings. The system keeps track of guest information, including check-in/check-out dates, room numbers, and the total bill for the stay.

## Features

- Add guests with details such as name, phone number, check-in date, check-out date, and room number.
- View all guests and their information, including the total bill.
- Check out guests and free up rooms for future bookings.
- Room availability is checked based on dates, ensuring there are no overlapping bookings.

## System Limitations

- Supports a maximum of 100 guests and 50 rooms.
- Room prices vary depending on the room number.
- Simple date validation is included to prevent double bookings.

## How to Compile and Run

To compile the program, use `gcc`:

```bash
gcc hotel_management.c -o hotel_management
```
To run the program: 
```bash
./hotel_management
```
How to Use
Add Guest: Input guest details including check-in and check-out dates. The system calculates the total bill based on room price and the number of nights.
View Guests: Displays a list of all current guests.
Check Out Guest: Removes a guest from the system, marking their room as available again.
