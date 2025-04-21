# Driver Drowsiness Detection System

A real-time system that detects driver drowsiness using computer vision and facial landmarks to prevent accidents caused by fatigue.

## Features
- Real-time eye tracking
- Blink counter
- Drowsiness alerts (visual and audio)
- Eye Aspect Ratio (EAR) calculation
- Facial landmark detection
- Continuous monitoring system

  <img width="1440" alt="Screenshot 2025-04-21 at 11 04 40 AM" src="https://github.com/user-attachments/assets/5cb6ed66-74a7-4392-880d-f7605a1a2065" />


## Files
- `blinkDetect.py`: Main detection script
- `alarm.wav`: Alert sound
- `eye.PNG`: Eye detection reference
- `eye_aspect_ratio.PNG`: EAR calculation diagram
- `face.PNG`: Facial landmarks reference

<img width="1440" alt="Screenshot 2025-04-21 at 11 04 33 AM" src="https://github.com/user-attachments/assets/f41da3a6-6468-46a6-af4a-3d893b63afa4" />

## Setup and Usage
1. Install required packages:
```bash
pip install opencv-python dlib scipy playsound numpy

Driver-Drowsiness-Detection-System/
├── README.md
├── alarm.wav
├── blinkDetect.py
├── eye.PNG
├── eye_aspect_ratio.PNG
└── face.PNG
## Trae AI
# Driver Drowsiness Detection System
This system helps prevent accidents by monitoring driver alertness through real-time eye tracking and drowsiness detection.

## What It Does
1. Eye Tracking
   
   - Continuously monitors both eyes
   - Tracks eye opening and closing
   - Detects blink patterns
   - Shows real-time eye landmarks
2. Blink Analysis
   
   - Counts total number of blinks
   - Calculates blink rate per minute
   - Displays current blink count
   - Monitors blink duration
3. Drowsiness Detection
   
   - Measures eye closure duration
   - Calculates Eye Aspect Ratio (EAR)
   - Triggers alerts for prolonged eye closure
   - Shows visual warning messages
4. Alert System
   
   - Visual alert with red warning text
   - Audio alarm for drowsiness
   - Real-time EAR value display
   - Emergency alerts for dangerous situations
5. Visual Feedback
   
   - Green dots showing eye landmarks
   - Eye region outline
   - Current metrics display
   - Status indicators
## Key Features
- Real-time processing
- Easy-to-read interface
- Non-intrusive monitoring
- Immediate alert system
- Continuous blink tracking
- Accurate drowsiness detection
