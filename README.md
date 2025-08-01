# tradingbotv1

Kraken Trading Bot - Minimal Flask Web App

This is a minimal Flask web application with login and dashboard functionality.

Setup Instructions:

1. Install dependencies:
   pip install flask flask-login werkzeug
   pip install cryptography
   pip install waitress
   pip install pandas

2. Run the app:
   python app.py
   set FLASK_APP=app
   flask init-db

3. Access the app in your browser:
   http://localhost:5000
   waitress-serve --host 127.0.0.1 --port 5000 app:app
