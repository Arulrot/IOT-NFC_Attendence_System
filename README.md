

# IoT NFC Attendance System

## Overview

The IoT NFC Attendance System is an advanced solution designed to streamline and automate the process of tracking employee attendance. By leveraging NFC technology and NodeMCU, this system captures unique NFC UIDs as employees clock in and out, ensuring precise and reliable attendance records.

## Features

- **NFC Technology**: Utilizes NFC tags for easy and quick attendance logging.
- **NodeMCU Integration**: Employs NodeMCU to send UID data to the cloud.
- **Google Apps Script**: Processes and records attendance times.
- **Real-time Notifications**: Sends instant updates to a designated Telegram group.
- **Data Storage**: Maintains attendance records in a Google Spreadsheet for easy access and analysis.
- **Automation**: Reduces manual entry errors and enhances operational efficiency.

## How It Works

1. **NFC Tag Scanning**: Employees scan their NFC tags on the NFC reader connected to the NodeMCU.
2. **Data Transmission**: NodeMCU sends the scanned UID to Google Apps Script.
3. **Attendance Logging**: Google Apps Script processes the UID and records the in/out times in a Google Spreadsheet.
4. **Notifications**: The system sends real-time notifications to a designated Telegram group.

## Setup and Installation

### Hardware Requirements

- NFC Reader
- NFC Tags
- NodeMCU
- Connecting Cables

### Software Requirements

- Arduino IDE
- Google Apps Script
- Telegram Bot

### Steps

1. **Configure NodeMCU**:
    - Install the necessary libraries in Arduino IDE.
    - Upload the provided code to NodeMCU.

2. **Set Up Google Apps Script**:
    - Create a new Google Apps Script project.
    - Copy the provided script and deploy it as a web app.
    - Update the NodeMCU code with your Google Apps Script URL.

3. **Configure Telegram Bot**:
    - Create a new bot on Telegram.
    - Update the Google Apps Script with your bot token and chat ID.

4. **Connect Hardware**:
    - Connect the NFC reader to the NodeMCU.
    - Ensure all connections are secure and power up the system.

## Usage

1. **Start the System**: Power up the NodeMCU and ensure it is connected to the internet.
2. **Scan NFC Tags**: Employees scan their NFC tags on the reader.
3. **Monitor Notifications**: Real-time updates will be sent to the Telegram group.
4. **Access Attendance Records**: Check the Google Spreadsheet for detailed attendance logs.

## Contributing

We welcome contributions to enhance the IoT NFC Attendance System. Feel free to fork the repository and submit pull requests.

