# python-email-automation
# 📧 Email Automation using Python (SMTP + SSL)

## Project Overview

This project demonstrates how to send emails securely using Python. It uses the **SMTP protocol with SSL encryption** and the built-in `email.message` module to send emails from a Gmail account.

The program allows the user to input the recipient's email and automatically sends a predefined message.

---

## Objectives

* Automate email sending using Python
* Use secure email transmission (SSL)
* Accept dynamic user input for recipient email
* Understand SMTP configuration with Gmail

---

## Technologies Used

* Python
* smtplib (for sending emails)
* ssl (for secure connection)
* email.message (for email formatting)

## Features

* Secure email sending using **SMTP_SSL**
* User input for receiver email
* Predefined subject and message
* Error handling using try-except block
* Simple and easy-to-understand implementation

## Project Structure

```bash
python-email-automation/
│
├── main.py        # Main Python script
└── README.md      # Project documentation
```

---

## How It Works

1. The user enters the recipient's email address.
2. The program creates an email using `EmailMessage`.
3. A secure SSL connection is established with Gmail SMTP server.
4. The sender logs in using email and App Password.
5. The email is sent successfully.

## How to Run

### Step 1: Install Python (if not installed)

### Step 2: Run the script

```bash
python main.py
```

### Step 3: Enter recipient email when prompted

## Gmail Configuration

* SMTP Server: `smtp.gmail.com`
* Port: `465` (SSL)

### Important:

* Do NOT use your normal Gmail password
* Use **Google App Password**

---

## Code Explanation

* `EmailMessage()` → Creates email structure
* `SMTP_SSL()` → Secure connection to server
* `login()` → Authenticates sender
* `send_message()` → Sends the email

---

## Security Warning

* Never expose your App Password in public repositories
* Always use environment variables or `.env` file in real projects

---

## Future Improvements

* Add multiple recipients support
* Add attachments (PDF, images)
* Dynamic subject and message input
* GUI interface using Tkinter
* Integration with web crawler for bulk emailing

---

## Conclusion

This project shows how Python can be used to automate email sending securely using SMTP and SSL. It is useful for real-world applications like notifications, alerts, and marketing emails.

---

## Author

Shreya Pandey
