# RFID-Based Attendance System

## Description
An efficient attendance system that uses an RFID module (RC522) with an ESP8266 microcontroller to scan and record attendance automatically. When an RFID tag is scanned, the user’s information is stored with full details in a spreadsheet for easy tracking and management.

## Features
- RFID-based attendance marking using RC522
- Automatic data logging with timestamp
- Stores attendance details in a spreadsheet (e.g., Google Sheets or Excel)
- Easy to use and setup
- Reduces manual errors in attendance tracking

## Technologies Used
- ESP8266 microcontroller
- RC522 RFID module

## Installation & Setup
1. Connect the RC522 RFID module to the ESP8266 following the wiring diagram.
2. Upload the provided code to the ESP8266.
3. Configure the spreadsheet connection (e.g., Google Sheets API credentials).
4. Scan RFID tags/cards to mark attendance.

## Usage
- Scan an RFID tag to record attendance.
- Attendance details (such as ID, name, date, and time) are automatically logged into the spreadsheet.
- Access and manage attendance data easily via the spreadsheet.

## Contributing
Feel free to contribute improvements or suggest features by opening issues or pull requests.

## License
MIT License
