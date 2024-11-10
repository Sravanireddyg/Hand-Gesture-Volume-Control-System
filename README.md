# Hand Gesture Volume Control System

This project provides a touch-free way to control your computer’s audio volume through hand gestures. Utilizing Python, OpenCV, and MediaPipe, this system tracks hand movements to adjust the volume based on the distance between the thumb and index finger.

## Features

- **Gesture-Based Volume Control**: Adjusts audio volume by measuring the distance between the thumb and index finger.
- **Real-Time Detection**: Captures hand movements using a webcam and updates volume instantly.
- **Volume Level Display**: Shows the current volume percentage and visual feedback on-screen.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Sravanireddyg/Hand-Gesture-Volume-Control-System.git
    cd Hand-Gesture-Volume-Control-System
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the volume control system**:
    ```bash
    python VolumeControlSystem.py
    ```

2. **Using Hand Gestures to Control Volume**:
    - Position your thumb and index finger in front of the camera.
    - Adjust the distance between your thumb and index finger to increase or decrease the volume.
    - Volume level will be displayed on the screen as a percentage.

## Requirements

Refer to the `requirements.txt` file for the list of dependencies. You can install them using the command:
```bash
pip install -r requirements.txt
```

## Author

[Sravani Reddy Gudibandi](https://github.com/Sravanireddyg)
