# Flask Form Submission App

## Overview

This is a simple Flask web application that allows users to submit their name and age through a form. Upon submission, the application takes the input and displays it on a new page.

### Features
- A form for entering **Name** and **Age**.
- The form data is sent to the backend using the POST method.
- The entered data is displayed on a separate page after submission.

## Requirements

Before running this project, ensure you have the following installed:
- Python (>= 3.6)
- Flask (>= 2.0.0)

### Dependencies

The main dependency for this project is the **Flask** web framework. You can install Flask using the following command:

```bash
pip install Flask
```
## Project Structure

├── app.py              # Main Flask application
├── templates
│   ├── index.html      # Form page
│   └── data.html       # Data display page
└── README.md           # Project instructions
