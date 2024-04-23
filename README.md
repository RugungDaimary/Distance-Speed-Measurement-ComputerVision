# Distance and Speed Measurement Using Single Camera

This project explores the fascinating field of computer vision, specifically focusing on the tasks of distance and speed measurement using a single camera setup. By leveraging the power of OpenCV (Open Source Computer Vision Library), this implementation demonstrates the ability to estimate distances and measure object speeds based on visual information captured by a camera.

## Contributors

- Rajnish Kumar (2K21/IT/139)
- Ritik (2K21/IT/145)
- Rugung Daimary (2K21/IT/151)

## Introduction

Accurate distance and speed measurement have numerous applications, including traffic monitoring and management, object detection and tracking, sports analytics and performance analysis, and robotics navigation and obstacle avoidance. This project aims to provide a practical solution for these tasks using a single camera setup and the OpenCV library.

## Implementation

- **Face Detection**: The system employs a pre-trained Haar Cascade classifier from OpenCV to detect human faces in each frame of the video feed, enabling the system to focus on important areas for analysis.

- **Focal Length Calculation**: The focal length of the camera is calculated using a known distance and width of a reference object, providing a foundation for distance estimation.

- **Distance Estimation**: Utilizing the calculated focal length, the system estimates the distance of objects (faces) from the camera in each video frame.

- **Speed Calculation**: By measuring the change in distance over time, the system calculates the speed of the object's movement.

- **Visualization and Output**: The project provides real-time visualization of the detected face, overlaid with information about the estimated distance and speed. Additionally, the processed video feed, including the distance and speed measurements, can be saved as an output video file.
