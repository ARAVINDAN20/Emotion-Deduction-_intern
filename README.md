# Emotion Detection Project

Welcome to the Emotion Detection project repository! This project utilizes deep learning and computer vision techniques to identify and display human emotions from facial expressions in real-time.

![Emotion Detection Demo](demo.gif)
![image](https://github.com/ARAVINDAN20/Emotion-Deduction-_intern/assets/116174602/116af0fc-72a0-4af5-96b8-1651f4dd1aef)

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Emotion Detection project aims to create an intuitive application capable of analyzing facial features and predicting emotions such as happiness, sadness, anger, fear, surprise, and more. This repository contains the code and resources developed during my internship at NullClass.

## Features

- **Facial Expression Recognition**: Detects and classifies emotions from images using a Convolutional Neural Network (CNN).
- **Real-Time Detection**: Processes uploaded images and provides instant emotion predictions.
- **User-Friendly Interface**: Developed with Tkinter, allowing users to easily upload images and view results.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - TensorFlow and Keras for deep learning
  - OpenCV for face detection
  - Tkinter for GUI development
  - Pillow (PIL) for image processing
## Data set
https://www.kaggle.com/datasets/msambare/fer2013
## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-username/emotion-detection.git
   cd emotion-detection
2. **Create and activate a virtual environment**:
   ```sh
   python -m venv venv
   .\venv\Scripts\activate  # On Windows
   source venv/bin/activate  # On macOS/Linux
3. **Install dependencies:**
   ``sh
   pip install -r requirements.txt
4. **Run the application**:
   ```sh
   python gui.py
After running the application, follow these steps:

5. **Upload an image**:
   - Click the "Upload Image" button to select an image file.

6. **View emotion prediction**:
   - The application detects faces in the image and predicts the emotion.
   - The predicted emotion is displayed on the interface.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
