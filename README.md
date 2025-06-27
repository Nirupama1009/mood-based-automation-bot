# Mood-Based WhatsApp Automation Bot

This mini project uses Python and WhatsApp Web automation to send pre-defined messages based on the user's current mood. 
It leverages web scraping and simple logic to identify moods and trigger appropriate responses.

# Features

- Detect mood based on user input or predefined keywords
- Automatically open WhatsApp Web
- Send appropriate messages to selected contacts
- Customizable moods and messages
- Lightweight and beginner-friendly Python script

# Tech Stack

- Python
- Selenium WebDriver
- time, datetime, os (standard libraries)
- WhatsApp Web (for automation)

# How It Works

1. User selects or inputs their current mood
2. Script launches WhatsApp Web
3. Chooses contact(s)
4. Sends mood-based message(s)

## 📂 Project Structure

 mood-based-automation-bot/
│
├── main.py # Main script to run the bot
├── mood_config.json # Customizable mood-message mappings
├── requirements.txt # Dependencies
└── README.md # Project documentation


## 🔧 Installation

git clone https://github.com/Nirupama1009/mood-based-automation-bot.git
cd mood-based-automation-bot
python -m venv venv
venv\Scripts\activate  # On Windows
pip install -r requirements.txt

# Usage :

 python main.py
- Then follow the on-screen instructions to choose a mood and target contact.

# Example Moods:

😊 Happy → "Hey! Just wanted to say I'm feeling great today! Hope you're too!"

😔 Sad → "Not feeling the best today... could use a chat 💬"

😠 Angry → "I need a break. Just venting 😤"

❤️ Romantic → "Thinking about you 💖"

You can edit mood_config.json to add your own moods and messages.

# Disclaimer:

  This bot uses Selenium automation to interact with WhatsApp Web. It is intended for educational purposes only. Use responsibly.







