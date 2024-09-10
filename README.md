# Virtual Keyboard with Hand Tracking

This project is a virtual keyboard application that uses hand tracking to detect gestures and input text. The keyboard is displayed on a webcam feed, and you can type by moving your hand over the on-screen keys.

## Requirements

The project requires the following Python packages:

- **`opencv-python`**: A Python library for computer vision that provides tools for image and video processing. It is used in this project to capture video from the webcam and process images to detect hand gestures.

- **`cvzone`**: A library that simplifies OpenCV tasks with a collection of utility functions and modules. In this project, it is used for hand tracking and drawing utilities to create the virtual keyboard.

- **`numpy`**: A fundamental package for scientific computing in Python. It provides support for large multidimensional arrays and matrices. This package is used for numerical operations and array manipulations.

- **`pynput`**: A library that allows you to control and monitor input devices such as keyboards and mice. In this project, it is used to simulate keyboard presses based on hand gestures detected by the application.

You can install these dependencies using the `requirements.txt` file. Run the following command to install them:

```bash
pip install -r requirements.txt
```

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/eyadrid/AI-Virtual-Keyboard.git
    cd AI-Virtual-Keyboard
    ```


2. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Connect your webcam and make sure it's working.

2. Run the application:

    ```bash
    python main.py
    ```

3. A window will open displaying the webcam feed with an overlay of the virtual keyboard. Move your hand over the keys to see them highlight.

4. When your hand is close to a key (within 30 pixels), the key is pressed and its character is added to the final text displayed at the bottom of the screen.

## Features

- Hand tracking to detect gestures and input text.
- On-screen virtual keyboard with highlighted keys.
- Real-time text input display.
  Troubleshooting
