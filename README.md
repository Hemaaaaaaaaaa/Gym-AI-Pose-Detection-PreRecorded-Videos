# Gym-AI-Pose-Detection-PreRecorded-Videos
# Gym AI Pose Detection

## Overview
The **Gym AI Pose Detection** project is an AI-powered application that detects and tracks body movements during exercises, providing real-time feedback and counting repetitions. It uses **MediaPipe Pose** for pose detection and displays key posture feedback to help users improve their workout form.

## Features
- Detects multiple exercises such as:
  - Squats
  - Push-ups
  - Dumbbell Curls
  - High Knees
  - Overhead Press
- Provides real-time feedback on posture and counts reps.
- Simple, user-friendly web interface using HTML, CSS, and JavaScript.
- Multi-angle pose detection and posture correction.

## Technologies Used
- **Flask**: Backend framework.
- **MediaPipe Pose**: For real-time human pose estimation.
- **OpenCV**: For video processing.
- **JavaScript, HTML, CSS**: For the frontend interface.

## Installation
1. Clone the repository:
   ```bash
   git clone  https://github.com/Hemaaaaaaaaaa/Gym-AI-Pose-Detection
   cd gym-ai-pose-detection

2.  Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

3. Install the required dependencies:
pip install -r requirements.txt

## Usage

1. Run the Flask application:
python app.py

2. Open your browser and navigate to http://127.0.0.1:5000 to access the web interface.

3. Start performing exercises in front of your webcam, and the system will automatically detect your movements, provide feedback, and count reps.

## Contributing
Feel free to fork this repository, submit issues, and send pull requests to enhance the project further.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
