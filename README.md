# Real-Time Object Detection

This project is a web-based real-time object detection application using TensorFlow.js and the COCO-SSD model. It uses a webcam to detect objects in the frame and provides details such as confidence levels and distances.

## Features
- Real-time object detection using the COCO-SSD model.
- Displays detected objects, their confidence levels, and calculated distances.
- Audio announcements for newly detected objects.
- Clean and responsive user interface.

## Technologies Used
- **HTML5, CSS3, JavaScript**: For building the frontend.
- **TensorFlow.js**: For running the COCO-SSD model in the browser.
- **Web Speech API**: For announcing detected objects.
- **WebRTC**: For accessing the webcam.

## Setup and Usage

### Prerequisites
- A modern web browser that supports WebRTC and TensorFlow.js (e.g., Chrome, Firefox, Edge).
- A device with a webcam.

### Steps to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/object-detection-app.git
   cd object-detection-app
