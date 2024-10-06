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
```
├── app.py              # Main Flask application
├── templates
│   ├── index.html      # Form page
│   └── data.html       # Data display page
└── README.md           # Project instructions
```

### Setup

1. Clone the repository (if applicable) or copy the files to your local machine.
2. Navigate to the project directory in your terminal.
3. Install Flask using pip if you haven't already

## Running the Project
1. Open a terminal/command prompt and navigate to the project folder.
2. Run the Flask application with the following command:
```bash
python app.py
```
3. Once the application is running, open your web browser and go to: 
http://127.0.0.1:5000/
4. You will see a form where you can enter your name and age.
5. After submitting the form, you will be redirected to another page that displays the submitted name and age.
