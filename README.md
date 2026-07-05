**Magic-Hand-cv**

A real-time Augmented Reality (AR) interaction engine using Python, OpenCV, and MediaPipe. It tracks hand gestures to render dynamic shields, portals, and energy beams through custom coordinate-based visual effects and physics.

🚀 Overview
magic-hand-cv is an interactive computer vision project that turns your webcam into a magical interface. By leveraging spatial hand-tracking, the engine maps hand landmarks in 3D space to trigger interactive VFX in real-time.

✨ Features
Spatial Hand-Tracking: Uses MediaPipe to map 21 3D landmarks for high-precision gesture detection.

Interactive VFX Engine:

Mandala Shields: Dynamically generated, rotating shields that respond to hand movement.

Portal Dimension Shift: An AR portal effect that masks reality and renders an alternate "dimension" in real-time.

Energy Beam Ultimate: A dual-hand interaction system that calculates midpoints to fire energy beams and trigger screen-shake physics.

Physics-Based Particles: A custom particle system that simulates magical embers and discharge effects.

🛠 Tech Stack
Language: Python

Vision/AR: OpenCV (Image processing, affine transformations, masking)

Tracking: MediaPipe (Hand landmark detection)

Math/Numerical: NumPy, Math (Coordinate geometry, rotation matrices)

📋 How to Use
Requirements:

Bash
pip install opencv-python mediapipe numpy

Run the Engine:

Bash
python hand_gesture1.py

Controls:

Shield: Open your hand (index and middle fingers up, ring and pinky fingers down).

Portal: Use the "Sling Ring" gesture (index and middle fingers up, ring and pinky fingers curled).

Energy Beam: Bring both open hands together until they are within 160 pixels of each other.
