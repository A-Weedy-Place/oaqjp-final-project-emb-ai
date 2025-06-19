# Emotion Detection Web Application

This project is a Flask-based web app that uses IBM Watson NLP to detect emotions from text. It identifies five emotions — anger, disgust, fear, joy, and sadness — and outputs the dominant emotion.

## Features

- Detects multiple emotions from user input
- Displays a formatted emotional breakdown
- Includes error handling for empty input
- Web interface with JavaScript and Bootstrap
- Packaged with unit tests and static code analysis (PyLint)

## How to Run

1. Clone the repository
2. Install dependencies (`flask`, `ibm-watson`, etc.)
3. Set your IBM Watson API credentials
4. Run the app:

```bash
export FLASK_APP=server:app
flask run --port=5001
