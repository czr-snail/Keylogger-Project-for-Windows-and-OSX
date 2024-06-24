This is the second basic project which is assigned to me as an intern at SlashMark IT Startup

Project Name: CyberKeylogger
Description
CyberKeylogger is a lightweight keylogging application developed in Python, designed to capture keyboard input on Windows and macOS systems. It provides functionalities to start and stop logging, clear logs, and download captured data in PDF and Word formats.

Features
Cross-Platform Compatibility: Supports both Windows and macOS operating systems.
Secure Logging: Logs keyboard input with timestamps for cybersecurity analysis.
User-Friendly Interface: Simple web-based control panel for starting, stopping, and managing logs.
Export Options: Download captured logs in PDF and Word formats for easy analysis.
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/CyberKeylogger.git
cd CyberKeylogger
Install Dependencies

Ensure Python 3.x is installed on your system.
Install Flask and other required packages using pip:
bash
Copy code
pip install flask pynput fpdf python-docx
Run the Application

Start the Flask server:
bash
Copy code
python app.py
Open your web browser and go to http://127.0.0.1:5000/ to access the control panel.
Usage
Start Keylogger: Click on "Start Keylogger" to begin capturing keyboard input.
Stop Keylogger: Click on "Stop Keylogger" to pause logging.
Clear Logs: Click on "Clear Logs" to delete all captured data.
Download Logs: Access /download_pdf and /download_word to download logs in PDF and Word formats, respectively.
Security Considerations
Data Privacy: Ensure logs are stored securely and access is restricted to authorized users only.
Legal Compliance: Use this tool responsibly and adhere to legal requirements regarding monitoring and privacy.
