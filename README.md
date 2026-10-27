# Handwritten Reader

**A simple way to turn study notes into speech.**

## About the Project

I built Handwritten Reader to make studying a little easier. Students often have pages of handwritten notes to go through, and I wanted to create something that could help them listen to their notes instead of always reading from the screen.

This project is a web application where users can upload an image of their notes, work with the text, listen to it using speech synthesis, and download the text as a file.

I am building this project step by step while learning how frontend and backend technologies work together.

## What I've Built

- **Image Upload:** Upload an image of handwritten notes or book pages.
- **Image Preview:** View the uploaded image on the webpage.
- **Text Input and Editing:** Enter or edit the text you want to listen to.
- **Text-to-Speech:** Listen to text directly in the browser.
- **Audio Controls:** Play, pause, resume, and stop speech.
- **Download Text:** Save the text as a `.txt` file.
- **Web Interface:** Use the application through a simple browser-based interface.

## Technologies I Used

- **HTML** — to build the structure of the webpage.
- **CSS** — to design the layout and appearance.
- **JavaScript** — to handle image previews, user interactions, speech controls, and text downloads.
- **Python** — to run the backend of the application.
- **Flask** — to serve the web application.
- **Web Speech API** — to convert text into speech directly in the browser.
- **Blob API** — to create a downloadable text file.

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Install Flask if it is not already installed:

   ```bash
   pip install flask
   ```

4. Run the Python application:

   ```bash
   python app.py
   ```

5. Open `http://127.0.0.1:5000` in your browser.

## What I'm Working On Next

One of the main improvements I want to make is automatic handwriting recognition. The goal is to extract text directly from an uploaded image, so users do not have to type it themselves.

I also want to improve the reading experience and make the application more useful for students who prefer listening to their study material.

## What This Project Has Taught Me

Working on Handwritten Reader has helped me practise JavaScript, connect a Python backend with a webpage, and understand how browser speech features can be used in a real application. It has also taught me that building a project involves testing, finding problems, and improving things one step at a time.

## Author

**GitHub:** [ektame07-svg](https://github.com/ektame07-svg)

I'm a student developer who enjoys learning by building projects and turning ideas into working applications.
