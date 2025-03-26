# slASL Translation

A project developed during JumboHack 2024 that translates American Sign Language (ASL) letters and numbers into speech and vice versa.

## Overview

**slASL Translation** enables communication through American Sign Language by leveraging a webcam-based machine learning model to recognize ASL signs and convert them to text and speech, as well as converting speech to ASL visuals.

### Features

- **Signs to Speech**:  
  - Webcam video feed is used to identify hand signs for letters A-Z and numbers 0-9.  
  - Recognized characters are displayed and read aloud using text-to-speech.

- **Speech to Signs**:  
  - Audio input is transcribed to text.  
  - The resulting text is mapped to corresponding ASL signs, displayed as images.

## How It Works

This project uses the [Google Teachable Machine](https://teachablemachine.withgoogle.com/) for supervised image classification.

- A model is trained with images labeled with each sign.
- It analyzes the webcam input in real-time.
- The model appends the label with the highest confidence to the website interface.

## Future Improvements

- Train the model with more image samples per sign.
- Improve background filtering to focus on hands, face, and gestures.
- Extend to dynamic (moving) signs for full-word or sentence translation.

## Tech Stack

- Google Teachable Machine (Machine Learning)
- HTML/CSS/JavaScript (Frontend)
- Web Speech API (Text-to-Speech and Speech Recognition)

## Acknowledgments

Developed during **JumboHack 2024** as a student project to improve accessibility and inclusivity through technology.
