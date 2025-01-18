# 💤Drowsiness-Detection-System 🚦
A real-time Drowsiness Detection System that uses computer vision and machine learning to monitor eye movements and detect signs of driver fatigue. This system leverages facial landmark detection and Eye Aspect Ratio (EAR) to trigger visual and auditory alerts, ensuring safer driving experiences. Implemented in Python using OpenCV, dlib, and pygame for a seamless and efficient solution. 🚗💤


## 📜 Project Overview
The Drowsiness Detection System uses computer vision and facial landmark detection to prevent accidents caused by drowsy driving. It detects fatigue based on the Eye Aspect Ratio (EAR) and triggers an alert with visual and auditory warnings when the threshold is crossed.


## 🎯 Features
- ✔️ Real-time detection of drowsiness using a webcam
- ✔️ Uses EAR to monitor eye closure duration
- ✔️ Triggers an audio alarm if drowsiness is detected
- ✔️ Displays visual alerts on the screen

## 🛠️ Technologies Used
Programming Language: Python 3.9.0
Libraries:
scipy for distance calculations
imutils for resizing the frame
dlib for facial landmark detection
pygame for audio alerts
cv2 (OpenCV) for video processing

## 🚀 Getting Started
### 1️⃣ Prerequisites
Before running the project, make sure you have the following installed:
- Python 3.9+
- pip (Python package manager)

### 2️⃣ Download Required Files
#### 📥 Downloading the Pre-trained Shape Predictor File
The ` shape_predictor_68_face_landmarks.dat file ` is a pre-trained model required for facial landmark detection.
Due to its large size, it is not included directly in this repository.

Please download the file from the official dlib website or other trusted sources.

Extract the `.bz2` file to get the `.dat` file. 

Place the `.dat` file in the resources/ folder of this repository.

#### 📢 Audio File: <br>

Include a `.wav` file named `alert.wav` in the resources/ folder.

### 3️⃣ Install Dependencies
Run the following command to install the required Python libraries:
```Python
pip install scipy imutils dlib pygame opencv-python  
```

## 🖥️ How to Run the Project
- Clone the repository:
```
git clone https://github.com/hk1105/drowsiness-detection-system.git
```
```
cd drowsiness-detection-system
```

- Navigate to the src/ directory:
```
cd src
```

- Run the main script:
```
python main.py
```

- Allow camera access when prompted.

- Press q to exit the program.


## 🌟 Conclusion
The Drowsiness Detection System is a step towards enhancing road safety by leveraging the power of computer vision and machine learning. With its real-time detection capabilities, the system serves as a proactive tool to prevent accidents caused by driver fatigue. By continuing to refine and innovate, this project has the potential to save lives and contribute to safer transportation systems.

We hope this project inspires others to explore similar solutions and advance the field of driver safety. Your support and contributions are invaluable—together, let's make roads safer for everyone! 🚦✨
