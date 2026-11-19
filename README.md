# SFSE
Description about the project 

A secure web-based file storage application that uses AES encryption to protect files and controlled access to ensure only authorized users can view, share, and download them.

Technologies Used

Python, Django, AES Encryption, HTML, CSS, JavaScript, Database

Tools Used

Visual Studio Code, Git & GitHub, Python

Key Features

- User Registration and Login
- OTP Verification
- AES File Encryption and Decryption
- Secure File Upload and Download
- Authorized File Sharing
- Activity Logging

Installation & Execution

git clone YOUR_REPOSITORY_URL
cd YOUR_PROJECT_FOLDER
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

Open in browser: "http://127.0.0.1:8000/"

Project Workflow

1. Register and log in.
2. Verify using OTP.
3. Upload files for AES encryption.
4. Store encrypted files securely.
5. Allow authorized users to access and download files.
