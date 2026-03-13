# ProVA – Productivity Voice Assistant

ProVA is a desktop-based productivity voice assistant built using Python.  
It automates common tasks such as file management, reminders, email operations, and spreadsheet handling using voice commands.

## Application Interface
<img width="1916" height="1015" alt="Screenshot 2026-03-11 211251" src="https://github.com/user-attachments/assets/bf0d7643-add1-4cf5-9bf7-155ea7e7b4fb" />

## Features

- **Voice Command Recognition** – Converts user speech into executable commands.
- **File & Folder Management** – Navigate, create, rename, and manage files using voice instructions.
- **Email Automation** – Perform basic email-related tasks through voice commands.
- **Excel Operations** – Execute spreadsheet-related actions and automate routine Excel tasks.
- **Reminder Scheduling** – Set and manage reminders for tasks and events.
- **Application Launching & Web Search** – Open applications and perform quick web searches via voice.
- **Interactive GUI** – User-friendly desktop interface built with PyQt5 for seamless interaction.

## Tech Stack

- Python
- PyQt5
- SpeechRecognition
- Pandas
- NumPy
- OS Module

## Project Structure
ProVA
│
├── modules/          # Functional modules
├── parser.py         # Command parser
├── router.py         # Command routing
├── voice_module.py   # Voice recognition
├── prova_ui.py       # GUI interface
├── data/             # configuration files
├── storage/          # saved user data

## Installation

Clone the repository:

git clone https://github.com/nidaqureshi-04/ProVA.git

Install dependencies:

pip install -r requirements.txt

Run the application:

python prova_ui.py

## Future Improvements

- Natural language command understanding
- Integration with calendar APIs
- Improved voice interaction
- Additional productivity integrations

## Author

Nida Qureshi  
BSc Data Science – Mumbai University
