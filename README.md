# MINI-Chatpot
## Description
This is a simple chatbot application built using Python's Tkinter library. It allows users to interact with the chatbot using both text and voice commands. The chatbot can respond with predefined answers or load responses from a JSON file.

## Features
- Text-based chat interface.
- Voice recognition for hands-free interaction.
- Text-to-speech responses for better accessibility.
- Load responses dynamically from a JSON file.
- Simple and user-friendly interface.

## Requirements
Make sure you have the following dependencies installed:
- Python 3.x
- Tkinter (comes pre-installed with Python)
- Pillow (for image processing)
- SpeechRecognition (for voice input)
- Pyttsx3 (for text-to-speech conversion)

## Installation
1. Clone or download this repository.
2. Install the required dependencies using pip:
   ```sh
   pip install pillow speechrecognition pyttsx3
   ```

## Usage
1. Run the script:
   ```sh
   python chatbot.py
   ```
2. Type a message in the input box and click "Send" or press Enter.
3. Click the "Voice" button to use voice input.
4. Load responses from a JSON file by clicking "Load File" and selecting a valid JSON file.

## File Structure
```
project-folder/
│-- chatbot.py      # Main application script
│-- abc.json        # Example response file (optional)
│-- README.md       # Documentation
```

## JSON Response Format
The chatbot can load responses from a JSON file structured as follows:
```json
{
  "questions_and_answers": [
    {"You": "hello", "Chatbot": "Hi there! How can I assist you?"},
    {"You": "bye", "Chatbot": "Goodbye! Have a nice day!"}
  ]
}## Description
This is a simple chatbot application built using Python's Tkinter library. It allows users to interact with the chatbot using both text and voice commands. The chatbot can respond with predefined answers or load responses from a JSON file.

## Features
- Text-based chat interface.
- Voice recognition for hands-free interaction.
- Text-to-speech responses for better accessibility.
- Load responses dynamically from a JSON file.
- Simple and user-friendly interface.

## Requirements
Make sure you have the following dependencies installed:
- Python 3.x
- Tkinter (comes pre-installed with Python)
- Pillow (for image processing)
- SpeechRecognition (for voice input)
- Pyttsx3 (for text-to-speech conversion)

## Installation
1. Clone or download this repository.
2. Install the required dependencies using pip:
   ```sh
   pip install pillow speechrecognition pyttsx3
   ```

## Usage
1. Run the script:
   ```sh
   python chatbot.py
   ```
2. Type a message in the input box and click "Send" or press Enter.
3. Click the "Voice" button to use voice input.
4. Load responses from a JSON file by clicking "Load File" and selecting a valid JSON file.

## File Structure
```
project-folder/
│-- chatbot.py      # Main application script
│-- abc.json        # Example response file (optional)
│-- README.md       # Documentation
```

## JSON Response Format
The chatbot can load responses from a JSON file structured as follows:
```json
{
  "questions_and_answers": [
    {"You": "hello", "Chatbot": "Hi there! How can I assist you?"},
    {"You": "bye", "Chatbot": "Goodbye! Have a nice day!"}
  ]
}
