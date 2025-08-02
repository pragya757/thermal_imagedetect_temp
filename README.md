# Thermal Vision Camera with Disease Detection

This project is a thermal vision camera system that captures live video from a webcam, applies a thermal filter, detects faces, and estimates temperature. The detected temperature is matched with potential diseases stored in a MySQL database.

# Features

Live Thermal Camera Feed: Applies a custom thermal filter to the webcam feed.
Face Detection: Uses OpenCV's Haar cascade to detect faces in real time.
Temperature Estimation: Maps thermal colors to estimated temperatures.
Disease Detection: Matches estimated temperature with disease data stored in a MySQL database.
GUI with Tkinter: Provides an interactive interface for capturing images and viewing results.

# Technologies Used

**Python**
**OpenCV (Computer Vision)**
**Tkinter (GUI)**
**MySQL (Database)**
**NumPy (Data Processing)**
**PIL (Image Processing)**

## System Requirements
- Python 3.8+
- OpenCV
- MySQL Server
- Tkinter (comes preinstalled with Python)
- NumPy, PIL (install via pip)

## Run Instructions
1. Clone the repo
2. Set up the MySQL database with disease-temperature pairs.
3. Run `python main.py`

# Usage

The live thermal camera feed will appear in the GUI.
Click the Capture button to analyze the detected face.
The system estimates temperature and checks for matching diseases.
A pop-up window displays the detection results.

# Screenshots

![Screenshot 2025-03-01 161106](https://github.com/user-attachments/assets/b3410505-2e0b-4ff4-ba45-0f87f573a207)



# Contributing

Feel free to contribute by submitting pull requests, reporting issues, or suggesting improvements.

# Contact

For any questions or suggestions, feel free to reach out!

Author: Pragya Paramita Sahoo Email: ppsahoo2005@gmail.com
Team: Ritwik Mathur Email:ritwikmathur2@gmail.com

