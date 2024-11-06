Wrath - An AI Chatbot
Wrath is a voice-enabled AI chatbot that performs a range of tasks, from natural conversation to managing your Google Calendar, sending emails, and fetching real-time weather reports. Wrath is designed to be a multi-functional assistant, supporting various everyday and productivity tasks through voice and text interactions.

Features
Voice Conversation: Engage in real-time conversation through voice.
Google Calendar Integration: Retrieve all or specific events from your Google Calendar.
Google Search: Opens your browser with search results based on your query.
Note Taking: Uses Notepad to store notes.
Email Sending: Send emails using Gmail.
Application Launching: Open applications like Music and VS Code.
Wikipedia Search: Directly fetch information from Wikipedia.
Real-Time Weather Reports: Get current weather information using OpenWeatherMap.

Installation
Prerequisites
Ensure Python is installed. All required modules are listed in the requirements.txt file.

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/wrath-ai-chatbot.git
cd wrath-ai-chatbot
Install dependencies:

bash
Copy code
pip3 install -r requirements.txt
API Setup
Google Calendar API
Enable the Google Calendar API for your account by following the instructions here.
Download the credentials.json file and place it in the project directory.
OpenWeatherMap API
Create an account on OpenWeatherMap to obtain an API key.

Create a keys.py file in the project directory with the following:

python
Copy code
EMAIL = "your email to send emails from"
PASSWORD = "password of your email"
DICT = {"recipient_name": "recipient_email"}  # Dictionary of email contacts
WEATHER_KEY = "your weather api key"
Usage
Start the Application:
Run the main script:

bash
Copy code
python main.py
Interacting with Wrath:

A GUI window will open, displaying the conversation.
Click on the speak icon to activate voice detection.
Wrath listens, converts your voice to text, and responds through the GUI and voice output.

