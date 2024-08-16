# Smart_biometric_attendance_System
## Overview
This project presents a **Biometric Attendance System** utilizing IoT technology with NodeMCU-ESP8266 and a fingerprint sensor. The system records attendance by scanning fingerprints, storing the data in Google Sheets, and providing a reliable, efficient method to track attendance, eliminating issues like proxy attendance.

## Project Objective
The main objective of this project is to develop a robust attendance management system that:
- Utilizes fingerprint biometrics for accurate identification.
- Automates the attendance recording process.
- Stores attendance data in real-time on Google Sheets.
- Prevents proxy attendance and ensures reliability.

## Key Features
- **Biometric Identification:** Fingerprint-based authentication using the R307 fingerprint module.
- **IoT Integration:** Real-time data storage on Google Sheets via the NodeMCU-ESP8266 WiFi module.
- **User Feedback:** LCD displays user information upon successful attendance logging.
- **Secure and Reliable:** Eliminates proxy attendance and provides accurate record-keeping.

## Methodology
The system is designed using the following components:
- **NodeMCU-ESP8266:** Serves as the central processing unit, interfacing with the fingerprint module and connecting to WiFi for data transmission.
- **R307 Fingerprint Module:** Captures and processes fingerprint data for user authentication.
- **LCD Display:** Provides real-time feedback to users by displaying messages like "Welcome" and user-specific details upon successful authentication.
- **Google Sheets:** Acts as the backend for storing attendance data, including timestamps and user details.

### System Flow
1. **Fingerprint Scanning:** Users place their finger on the R307 sensor.
2. **Data Processing:** The fingerprint is processed and matched against stored data.
3. **Attendance Logging:** On successful authentication, the attendance data (date, time, name, roll number) is sent to Google Sheets.
4. **Feedback:** The LCD displays a personalized welcome message.

## Hardware Setup:

1.Connect the NodeMCU-ESP8266 to the R307 fingerprint sensor and LCD display as per the circuit diagram.
2.Ensure a stable WiFi connection for data transmission.

## Software Configuration:

1.Install the required libraries in the Arduino IDE.
2.Upload the code to the NodeMCU-ESP8266.
3.Set up the Google Sheets API and update the code with your credentials.

## Run the System:

Power up the NodeMCU-ESP8266.
The system will start recording attendance upon fingerprint verification.
