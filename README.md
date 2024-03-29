<br/>
<p align="center">
  <h3 align="center">Real Time Object Detection </h3>

  <p align="center">
    <a href="https://github.com/SrikarKumar20/Real-time-object-detection"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/SrikarKumar20/Real-time-object-detection/total) ![Contributors](https://img.shields.io/github/contributors/SrikarKumar20/Real-time-object-detection?color=dark-green) ![Issues](https://img.shields.io/github/issues/SrikarKumar20/Real-time-object-detection) ![License](https://img.shields.io/github/license/SrikarKumar20/Real-time-object-detection) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [Authors](#authors)

## About The Project


This project implements a real-time object detection system using OpenCV. The system detects objects in live video streams  using a pre-trained deep learning model. It provides a user-friendly interface for configuring detection parameters and visualizing the detected objects.

## Built With

Programming Languages:
Python: Python serves as the primary programming language for developing the real-time object detection system. Its extensive libraries and frameworks for machine learning and computer vision, such as TensorFlow and PyTorch, facilitate model development and deployment.

Deep Learning Frameworks:
TensorFlow: TensorFlow provides a powerful framework for building and training deep learning models, including object detection models. Its flexibility and scalability make it suitable for large-scale projects like real-time object detection.
PyTorch: PyTorch is another popular deep learning framework known for its dynamic computation graph and ease of use. It enables rapid prototyping and experimentation with different model architectures and training strategies.

Computer Vision Libraries:
OpenCV: OpenCV (Open Source Computer Vision Library) is a fundamental tool for computer vision tasks, offering a wide range of functionalities for image and video processing, feature extraction, and object detection. It is instrumental in preprocessing video streams and post-processing detected objects.


## Getting Started

Welcome to the Real-Time Object Detection project! This guide will help you set up your development environment, train object detection models, and deploy a real-time object detection system.

### Prerequisites

Hardware Requirements:

A computer with a GPU (NVIDIA GPU recommended) for accelerated training and real-time inference.
Webcam or video input device for real-time video stream processing.
Software Requirements:

Python (3.6 or later)
TensorFlow or PyTorch
OpenCV
Jupyter Notebook (optional)
Docker (optional)

### Installation

Python Installation:

Download and install Python from the official website: python.org
Ensure that Python is added to the system PATH during installation.

Library Installation:

Open a terminal or command prompt.
Install TensorFlow or PyTorch using pip:
pip install tensorflow
or
pip install torch torchvision

Install OpenCV:
pip install opencv-python

Install numpy:
pip install numpy

Install imutils:
pip install imutils

Optional: Jupyter Notebook Installation:

Install Jupyter Notebook to facilitate interactive development:
pip install jupyter


## Usage

1)Run the Script:
Execute the Python script using your preferred method, such as running it from the command line or using an integrated development environment (IDE). Ensure that all prerequisites, including Python and the required packages, are installed.

2)Webcam Initialization:
The script will initialize the webcam and start capturing frames from it.

3)Object Detection:
Once the webcam is initialized, the script will perform real-time object detection on the captured frames using the MobileNet SSD model. Objects belonging to classes such as person, car, bicycle, etc., will be detected and labeled in the video stream.

4)Display:
The detected objects will be highlighted with bounding boxes and labeled with their corresponding class names and confidence scores. The annotated video stream will be displayed in a window titled "Frame".

5)Quit:
To exit the application, press the 'q' key on your keyboard. This will terminate the script and close the video stream window.

6)Performance Metrics:
After quitting the application, the script will display performance metrics, including the elapsed time and approximate frames per second (FPS) achieved during object detection.

7)Cleanup:
The script will perform cleanup tasks, such as closing any open windows and releasing the webcam resources.

8)Customization:
You can customize various parameters in the script, such as the minimum confidence threshold for object detection (confidence > 0.2), the classes to detect, and the colors used for bounding boxes. Modify these parameters according to your specific requirements.

By following these steps, you can utilize the provided code to perform real-time object detection using the MobileNet SSD model and OpenCV.


## Roadmap

See the [open issues](https://github.com/SrikarKumar20/Real-time-object-detection/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/SrikarKumar20/Real-time-object-detection/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/SrikarKumar20/Real-time-object-detection/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Authors

* **Srikar Kumar** - *Comp Sci Student* - [Srikar Kumar](https://github.com/SrikarKumar20) - *SRM UNIVERSITY*


