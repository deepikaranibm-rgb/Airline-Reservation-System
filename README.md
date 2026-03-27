# Airline Reservation System

A web-based airline reservation system built with Python Flask.

## Features

- User registration and login
- Flight search and booking
- Booking management
- Payment processing
- Drowsiness detection

## Requirements

See `requirements.txt` for all dependencies.

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Initialize the database:
   ```bash
   python init_db.py
   ```

3. Run the application:
   ```bash
   python app.py
   ```

The application will be available at `http://localhost:5000`

## Project Structure

- `app.py` - Main Flask application
- `database.py` - Database models and configurations
- `init_db.py` - Database initialization script
- `templates/` - HTML templates
- `static/` - CSS and JavaScript files
- `drowsiness_detection/` - Drowsiness detection module
