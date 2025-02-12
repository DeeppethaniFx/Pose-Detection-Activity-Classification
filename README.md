Real-Time Pose Estimation & Activity Recognition

Overview

This project utilizes MediaPipe's Pose Detection module to recognize and track human movements in real-time, specifically detecting and counting squats and push-ups. By analyzing body joint angles, the system can differentiate between exercises and count repetitions automatically.

Features

1. Real-time pose detection using MediaPipe
2. Automatic detection of squats and push-ups
3. Repetition counting based on movement states
4. Accurate angle-based analysis to differentiate activities
5. Works on both video files and webcam feed

Technologies Used

1. Python
2. MediaPipe (for pose estimation)
3. OpenCV (for video processing)
4. NumPy (for mathematical computations)

How It Works

1. Pose Detection:
The system extracts key body landmarks from video frames using MediaPipe.

2. Angle Calculation:
Specific angles (knee, elbow, and torso) are computed based on key joint positions.

3. Activity Differentiation:
Squats: Identified based on knee bending and upright torso position.
Push-ups: Identified based on elbow bending and straight body posture.

4. Repetition Counting:
Movement transitions (e.g., standing → squatting → standing) trigger repetition counts.

Angles Used for Detection


Future Improvements

1. Support for additional activities (e.g., jumping jacks, lunges)
2. Enhancing accuracy using machine learning models
3. Adding a GUI for easier interaction

