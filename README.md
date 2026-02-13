Voice-Controlled Desktop Assistant using Python

A simple Python-based voice assistant that performs basic tasks using voice commands.

## Features
- Wikipedia search
- Open websites (Google, YouTube, StackOverflow)
- Tell current time
- Voice interaction

## Tech Stack
- Python
- pyttsx3
- SpeechRecognition
- Wikipedia API

## How to Run
1. Clone this repository
2. Install dependencies:
   pip install -r requirements.txt
3. Run the assistant:
   python jarvis.py

## How It Works

The assistant captures voice input from the microphone using the SpeechRecognition library.
The recognized text is matched with predefined commands.

Based on the command, the assistant performs tasks such as:

- Opening websites via webbrowser
- Fetching summaries using Wikipedia API
- Speaking responses using pyttsx3 text-to-speech engine

The system runs in a continuous loop, enabling real-time voice interaction.


## Note
Microphone access is required.

## Future Improvements

- Add wake-word detection ("Hey Jarvis")
- Integrate AI conversation model
- Add desktop automation features
- Build GUI interface
- Cross-platform support

