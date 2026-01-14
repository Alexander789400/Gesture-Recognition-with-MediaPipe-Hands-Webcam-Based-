# Gesture-Recognition-with-MediaPipe-Hands-Webcam-Based-
# Computer Vision Project
Project Overview :

This project implements real-time hand gesture recognition using a pre-trained MediaPipe Hands model and a live webcam feed.
The system detects hand landmarks, classifies predefined gestures, and triggers interactive actions such as background color changes and sound playback.

The project runs entirely in the browser using JavaScript and does not require model training.

Objectives :

Detect hands from live webcam input

Identify hand gestures in real time

Display hand landmarks overlay

Trigger actions based on recognized gestures

Count gesture occurrences dynamically

Technologies Used :

MediaPipe Hands (Pre-trained ML model)

JavaScript

HTML5 & CSS3

Gesture	Detection Logic	Action Triggered :

👍 Thumbs Up	Thumb up, others down	Green background

✌️ Peace Sign	Index & middle up	Blue background + sound

✋ Open Palm	All fingers up	Yellow background

✊ Fist	All fingers folded	Red background

🤟 Rock Sign / I Love You	Thumb + index + pinky up	Purple background

👌 OK Sign	Thumb touches index	Orange background

How It Works  :

Webcam captures live video frames

MediaPipe Hands detects the hand and extracts 21 landmarks

Finger states (up/down) are calculated using landmark positions

Gestures are recognized using rule-based logic

Actions are triggered based on detected gesture

Hand landmarks are drawn on canvas in real time

Project Structure :

gesture-recognition/

│

├── index.html

├── style.css

├── script.js

└── sound/ mixkit-alarm-clock-beep-988.wav
    

How to Run the Project :

Clone or download this repository

Ensure the sound file is inside the sound/ folder

Open index.html in Google Chrome / Microsoft Edge

Allow webcam access

Perform gestures in front of the camera

Features :

Real-time performance (~30 FPS)

Accurate hand landmark detection

Interactive UI feedback

Gesture occurrence counter

Modular and readable code

No backend or model training required
 
Future Enhancements :

Support for dynamic gestures

Multi-hand gesture recognition

Gesture-controlled applications (slides, games)

ML-based gesture classification

Mobile responsiveness

Author :

Alexander Roy
