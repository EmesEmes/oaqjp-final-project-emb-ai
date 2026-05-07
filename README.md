# Final project

## Emotion Detection App

A web application that analyzes text and detects emotions using IBM Watson NLP.

## Technologies
- Python
- Flask
- IBM Watson NLP API

## Project Structure
```
├── emotion_detection.py   # Watson NLP emotion detection function
├── server.py              # Flask web server
├── templates/
│   └── index.html         # Frontend
└── static/
    └── mywebscript.js     # JavaScript for UI interactions
```

## How it works
1. User enters text in the web interface
2. The app sends the text to IBM Watson NLP API
3. The API returns emotion scores for: anger, disgust, fear, joy and sadness
4. The app displays the scores and the dominant emotion
