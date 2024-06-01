# Face Detection with Live Video Feed

Welcome to the Face Detection with Live Video Feed project! This project uses OpenCV to capture video and detect faces and eyes in real-time through a web interface powered by Flask.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project demonstrates real-time face and eye detection using OpenCV. It captures video from your webcam and processes it to detect faces and eyes. The processed video feed is displayed in a web interface using Flask.

## Features

- Real-time video capture from webcam
- Face detection using Haar cascades
- Eye detection within detected faces
- Web interface to display the processed video feed

## Installation

1. **Clone the repository:**
    ```sh
    git clone "https://github.com/Anudeep007-hub/FaceDetection.git"
    ```
2. **Navigate to the project directory:**
    ```sh
    cd FaceDetection
    ```
3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```
4. **Download the Haarcascade files:**
    - Download `haarcascade_frontalface_default.xml` and `haarcascade_eye.xml` from the OpenCV GitHub repository or other sources, and place them in a folder named `Haarcascades` in the project directory.

5. **Run the application:**
    ```sh
    python Face_Detection.py
    ```

## Usage

1. **Start the application:**
   - Run the `Face_Detection.py` script to start the Flask web server.

2. **Access the web interface:**
   - Open your web browser and navigate to `http://127.0.0.1:5000/`.

3. **View the live video feed:**
   - The web interface will display the video feed from your webcam with detected faces and eyes highlighted.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to create a pull request or open an issue.

1. **Fork the repository.**
2. **Create your feature branch:**
    ```sh
    git checkout  black
    ```
3. **Commit your changes:**
    ```sh
    git commit -m 'Add some feature'
    ```
4. **Push to the branch:**
    ```sh
    git push origin black
    ```
5. **Open a pull request.**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy exploring real-time face detection with this project! If you encounter any issues, feel free to open an issue on GitHub.
