BlightScript: A Windows Desktop Interaction Demo

Overview

Blight is a Python-based proof-of-concept application designed to demonstrate advanced desktop interaction techniques on Windows systems. It showcases the use of GUI manipulation, audio playback, browser automation, and keyboard input detection to create an immersive user experience. This project is intended for educational purposes, such as learning about system-level programming, GUI automation, and process management in Python. It is not intended for malicious use, and users are responsible for ensuring compliance with all applicable laws and ethical guidelines.

Features:

Initial Notification Window: Displays a centered window with the message "Good luck buddy :)" for 2 seconds upon startup.



Dynamic GUI Elements:

A persistent window (200x100 pixels) that smoothly follows the mouse cursor, updating its position every millisecond.



Randomly positioned windows (400x180 pixels) that spawn every 0.01 seconds, displaying messages.



A taskbar-blocking window that spans the width of the screen at the bottom, obstructing access to the Windows taskbar.



Audio Playback: Plays a looping MP3 audio file (e.g., music.mp3) and generates intermittent creepy sound effects using system beeps.



Browser Automation: Opens predefined URLs in the default web browser to enhance the immersive experience.

Controlled Termination: The program can be safely terminated by simultaneously pressing the keys 1, 9, and 0, triggering a clean shutdown sequence with audible feedback.

Platform: Windows only (due to reliance on winsound and ctypes for system interactions).
