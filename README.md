# Face Recognition Project

A simple face recognition project using `face_recognition` and OpenCV. This application detects and recognizes faces in real-time through the webcam feed and compares them with known faces from a specified folder.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Troubleshooting](#troubleshooting)
- [License](#license)

## Overview

This project uses the `face_recognition` library to recognize faces in a webcam feed. Known faces are compared to the faces detected in real-time, and their names are displayed on the screen. If the detected face does not match any of the known faces, it will be labeled as "Unknown."

## Features

- Real-time face recognition using a webcam.
- Comparison of detected faces with known faces stored in a folder.
- Displays the recognized person's name on the screen.
- Can handle multiple faces in a single frame.

## Installation

To run this project, you need Python 3.x and the required dependencies. Follow the steps below to set up the environment:

### Prerequisites

- Python 3.x
- OpenCV
- face_recognition
- numpy

### Directory
face_recognition_project/
│
├── known_faces/                  # Folder for storing images of known people
│   ├── person1.jpg               # Example image of person 1
│   ├── person2.jpg               # Example image of person 2
│   └── ...                       # More images
│
├── face_recog.py                 # Main script to run the face recognition
├── requirements.txt              # List of required Python dependencies
└── README.md                     # Project README


### Step 1: Clone the repository

```bash
git clone https://github.com/yourusername/face_recognition_project.git
cd face_recognition_project
