# ProVA – Productivity Voice Assistant

ProVA is a desktop-based productivity voice assistant built using Python.  
It automates common tasks such as file management, reminders, email operations, and spreadsheet handling using voice commands.
## Application Interface
![ProVA Interface](prova-ui.png)
## Features

- Voice command recognition
- File and folder management
- Email task automation
- Excel operations
- Reminder scheduling
- App Launching and Web Search 
- GUI interface for interaction

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
