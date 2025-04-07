# Console-Based OTP Sender Project (Python)

This is a console-based Python project that demonstrates how to generate a One-Time Password (OTP), send it to an email address using Google SMTP, and use both built-in and user-defined functions for modular code design.

## ✨ Features

- Console-based user interaction
- OTP generation using Python's `random` module
- Email sending via Google SMTP server
- Modular code structure using built-in and user-defined functions
- Basic input validation

### Files:
- `main.py`: Entry point of the application
- `otp_generator.py`: Contains the OTP generation logic (user-defined function)
- `email_sender.py`: Handles email sending using Google's SMTP server
- `README.md`: Project documentation

## 🛠️ Built-in Modules Used

- `random` – for generating the OTP
- `smtplib` – for sending emails via SMTP
- `ssl` – for secure connection
- `time` – (optional) for OTP expiration or delays

## 🔧 How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/otp-sender.git
   cd otp-sender
