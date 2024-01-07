# Anantadi_Advertisement-Insertion-with-Occlusion-Handling
Overview
This project aims to develop a computer vision solution that seamlessly inserts a specified advertisement image into a given video while gracefully handling occlusions. The implementation involves real-time processing, dynamic occlusion handling, user-friendly interaction for Region of Interest (ROI) selection, and optimization of video output quality.

Requirements

Python 3.x
OpenCV
NumPy

Installation
pip install opencv-python numpy

Usage
Clone the Repository:
git clone https://github.com/bikashparamanik/Anantadi_Advertisement-Insertion-with-Occlusion-Handling.git

Navigate to the Project Directory:
cd Advertisement-Insertion

Run the Code:
python advertisement_insertion.py

Follow On-screen Instructions:
Select the occlusion region in the sample video.
Observe real-time insertion of the advertisement.
Code Structure:
advertisement_insertion.py: Main script for video processing and advertisement insertion.
occlusion_handling.py: Module containing occlusion handling strategies.
utils.py: Utility functions for image manipulation and display.

Occlusion Handling Strategies:
The occlusion_handling.py module implements dynamic occlusion handling strategies, including:
Region of Interest (ROI) Extraction: Extracts the specified occlusion region from video frames.
Advertisement Resizing: Resizes the advertisement image to match the dimensions of the ROI.
Alpha Blending: Uses alpha blending to seamlessly integrate the advertisement into the video, considering the transparency information.

Insights and Challenges:

The implementation involves overcoming challenges such as real-time processing optimizations, dynamic occlusion handling, user interaction design, video output quality optimization, and code robustness across various scenarios. Insights gained during the development process contribute to a robust and efficient solution.
