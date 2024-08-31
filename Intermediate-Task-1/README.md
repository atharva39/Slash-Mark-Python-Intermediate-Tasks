# KKWBOT (Chat Bot)

KKWBOT is a conversational chatbot designed to provide information about KKWagh Institute of Engineering, Nashik. This chatbot utilizes Natural Language Processing (NLP) techniques to understand user queries and provide relevant responses based on a pre-defined set of data.

## Features
- Interactive GUI: Built with Tkinter, the GUI allows users to interact with the chatbot through a graphical interface.
- Voice Responses: Uses pyttsx3 for text-to-speech conversion to provide voice responses.
- Customizable Appearance: Offers options to change fonts and color themes within the GUI.
- Knowledge Base: Responds to queries related to KKWagh Institute's history, infrastructure, and facilities based on the content from chatbot1.txt and chatbot2.txt.
- Greeting and Introduction: Includes predefined responses for greetings and introduction queries.
- Dynamic Response Generation: Utilizes TF-IDF and cosine similarity for generating responses based on the content of the provided text files.

## Installation
1. Install dependencies from the requirements.txt file using:
```
pip install -r requirements.txt
```
2. Download NLTK data: Ensure that the NLTK data is downloaded by running the following in a Python environment:
```
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

## Usage
1. Run the GUI ChatBot:
```
python bot-gui.py
```
2. Interact with the ChatBot:
- Enter queries related to KKWagh Institute into the input field.
- Click "Send" or press Enter to submit your query.
- The chatbot will provide text and/or voice responses based on the query.

## Files and Their Responsibilities
- gui.py: Contains the Tkinter-based GUI code for the chatbot.
- bot-instructions.py: Contains the logic for processing user input and generating responses.
- chatbot1.txt: Contains information about KKWagh Institute.
- chatbot2.txt: Contains information about medical facilities at KKWagh Institute.
