# Ai-assistant
There is an simple AI assistant 
🧠 AI Voice Assistant (Python)
This is a simple voice-controlled AI assistant built with Python. It can perform a variety of tasks like searching Wikipedia, sending emails, opening websites/applications, controlling system functions, and managing reminders.

📦 Features
🎤 Voice recognition with speech_recognition

🔊 Text-to-speech with pyttsx3

🌐 Wikipedia and Google search

📅 Tell the current time

📧 Send emails (Gmail SMTP)

🧮 Open applications (Notepad, Calculator, Chrome, VS Code)

🔁 System control (Shutdown, Restart, Lock, Sleep)

🔈 Volume control (Up, Down, Mute)

📋 Set and read reminders

🛠️ Requirements
Install the required Python libraries using:

bash
Copy
Edit
pip install pyttsx3 SpeechRecognition wikipedia pyautogui
Also ensure:

Python 3.6+

Microphone access

Internet connection for web-based tasks

⚙️ How to Use
Update file paths and credentials in the script:

Replace YourUsername in app/music paths.

Replace email credentials in send_email() function.

Run the script:

bash
Copy
Edit
python AI_Final.py
Give voice commands, such as:

"Search Wikipedia for Python"

"Open YouTube"

"What is the time"

"Play music"

"Shutdown"

"Set reminder"

"Get reminders"

🔒 Security Note
Do NOT hardcode your real email and password in production. Use environment variables or a secure credential store.

📁 Files
AI_Final.py: Main Python script

reminders.txt: Stores user reminders (created automatically)

📌 To-Do / Improvements
Add wake word detection (e.g., “Hey Assistant”)

Replace smtplib with OAuth2 for secure email

GUI integration using Tkinter or PyQt

Multilingual support
