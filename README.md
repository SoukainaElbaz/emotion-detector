# Final Project: Emotion Detector

This repository contains the **Final Project** for the Emotion Detection web application using Watson NLP.

## Project Description

The application analyzes a sentence and detects the emotional tone present in the text.

The detected emotions include:

- anger
- disgust
- fear
- joy
- sadness

The system also determines the **dominant emotion** among these values.

## Technologies Used

- Python
- Flask
- Watson NLP API
- Requests
- Pylint
- Unit testing with unittest

## Project Structure


oaqjp-final-project-emb-ai/
│
├── EmotionDetection/
│ ├── init.py
│ └── emotion_detection.py
│
├── templates/
│ └── index.html
│
├── server.py
├── test_emotion_detection.py
└── README.md


## Running the Application

Navigate to the project directory:


cd oaqjp-final-project-emb-ai


Run the Flask server:


python server.py


Then open:


http://127.0.0.1:5000


Enter a sentence and click **Analyze Emotion** to see the detected emotions.

## Author

Soukaina Elbaz
