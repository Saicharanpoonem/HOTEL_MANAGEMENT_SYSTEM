# HOTEL_MANAGEMENT_SYSTEM - THE ROYAL MANSION

## Overview
This Python script is a hotel management system for **The Royal Mansion**, a fictional hotel. It enables hotel staff to manage bookings, customer records, room service, and payments efficiently.

## Features
- **Room Booking**: Book rooms by entering customer details and stay duration.
- **Room Information**: Display details of available room types and amenities.
- **Room Service**: Manage orders from an in-house restaurant menu.
- **Payment Processing**: Handle payments with multiple options and generate bills.
- **Customer Records**: Maintain and display records of all customers.

## Requirements
- Python 3.x
- JSON module (built-in)
- datetime module (built-in)

## How to Use

1. Clone the repository or download the script.
2. Run the script using Python:
   ```
   python hotel_management.py
   ```
3. Navigate through the menu options:
   - `1`: Booking
   - `2`: Rooms Info
   - `3`: Room Service (Menu Card)
   - `4`: Payment
   - `5`: Record
   - `0`: Exit

## Code Structure

### Global Variables
The script uses global variables to store customer data such as names, phone numbers, addresses, check-in/check-out dates, room types, and payment details.

### Functions
- **load_data()**: Load existing customer data from a JSON file.
- **save_data()**: Save customer data to a JSON file.
- **Home()**: Main menu function.
- **Booking()**: Handles room bookings.
- **Rooms_Info()**: Displays information about room types and amenities.
- **restaurant()**: Manages restaurant orders.
- **Payment()**: Processes payments and generates bills.
- **Record()**: Displays all customer records.

## Data Persistence
Customer data is stored in a file named `customer_data.json` to ensure persistence across sessions. The file is automatically created if it does not exist.

## Example Workflow
1. Start the application.
2. Select `1` to book a room by providing customer details, check-in/check-out dates, and selecting a room type.
3. Use `3` to place room service orders.
4. Finalize payment using `4`.
5. View all records with `5`.

## Menu Card
A full menu is available within the `restaurant()` function, allowing customers to order beverages, main courses, desserts, and more.

## Contribution
Feel free to fork this repository and submit pull requests. Suggestions and improvements are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.
