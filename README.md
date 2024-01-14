# Keystroke Logger Project

## Overview

This project is a simple keylogger implemented in Python using the pynput library. 
It captures keyboard input and sends email notifications with the logged keystrokes.

**Note:** This project is intended for educational purposes only.

#Screenshot
![keylogger](https://github.com/Hackersentry/keylogger/assets/117862080/fed2c4d5-4161-4351-ae64-5bc80bb29732)

## Requirements

- Python 3.x
- pynput library (install using `pip install pynput`)

## Setup

1. **Clone or Download:**
   - Clone this repository to your local machine using the following command:
     bash
     git clone https://github.com/Hackersentry/keylogger.git
     
   - Alternatively, download the ZIP file and extract it to your desired location.

2. **Install Dependencies:**
   - Navigate to the project directory:
     bash
     cd keylogger
     
   - Install the required dependencies:
     bash
     pip install -r requirements.txt
     

3. **Configure Email Settings:**
   - Open the script (`keylogger.py`) in a text editor.
   - Replace the following placeholders in the script with your actual email addresses, password, and SMTP server details.
     - `<your_email@gmail.com>` with your actual email address.
     - `<destination_email@gmail.com>` with the email address where you want to receive notifications.
     - `<your_email_password>` with the password of your email account.
     - `<smtp_server>` with the address of your SMTP server.
     - `<smtp_port>` with the port number of your SMTP server.

4. **Run the Script:**
   - Execute the script:
     bash
     python keylogger.py
     

## Usage

- Once the script is running, it will capture keystrokes and periodically send email notifications.
- Adjust the logging frequency, email content, or encryption methods based on your preferences.

## Ethical Considerations

This project should only be used for educational purposes. Ensure that you respect privacy and legal boundaries. Do not use this tool for malicious activities, and be aware of the potential ethical implications.

## Legal Compliance

Make sure that your usage of this project complies with relevant privacy laws and regulations. Clearly state the legal implications and usage restrictions in any documentation associated with this project.

## Disclaimer

The author is not responsible for any misuse or damage caused by this project. Use it responsibly and at your own risk.

