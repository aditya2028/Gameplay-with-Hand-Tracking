# Gameplay-with-Hand-Tracking
Created a Computer Vision Game with Hand Tracking using OpenCV and Mediapipe 
# Computer Vision Game basics:
The project involves using OpenCV and Mediapipe to create a computer vision game with hand tracking as the joystick.
Mediapipe is used to track 21 points of the hand, and the author recommends reading the official MediaPipe Hands guide for more details.
# Creating the game with Pygame:
The game involves swatting mosquitoes for points and avoiding swatting bees, all within a time limit.
Integration of Pygame with Mediapipe for the computer vision game is showcased.
# Installing Pygame:
Installation of Pygame library is simple using the 'pip install pygame' command.
# Main files of the computer vision game:
The main files to start and manage the game events, including hand tracking, are explained.
Rectangles are used to explain the concept of overlapping events.
# Adding hand as a controller (Computer Vision):
The author uses Mediapipe to generate a 3D map of 21 points of the hand and integrates this into the game.
A code example for hand tracking with Mediapipe Hands is provided.
# How to give the command?:
The command to control the game involves using landmark points to determine if the hand is open or closed.
The hand is considered closed when the highest point (12) is lower than the point before the palm (9).
# Final computer vision game:
The game is completed by integrating all the elements and can be played with a webcam.
