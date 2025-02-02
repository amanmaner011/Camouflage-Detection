# Camouflage Detection

![Python](https://img.shields.io/badge/Language-Python-blue)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Introduction

Camouflaged Target Acquisition is a critical aspect of modern defense and surveillance systems, presenting unique challenges in detecting concealed threats within complex environments. This project focuses on the detection, tracking, and counting of camouflaged objects with alert generation using deep learning techniques, particularly leveraging YOLOv8 and the Segment Anything Model.

## Repository Structure

- `src/`: Contains the source code for the project.
- `main.py`: Main script for running camouflage detection with alert generation
- `Report - Camouflage Detection.pdf`: Detailed project report.
- `PPT - Camouflage Detection.pptx`: Presentation on Camouflage Detection.
- `2 sec sample video.mp4`: Sample video used for testing.
- `Detected Camaflouge .mp4`: Video showing the detected camouflaged objects.
- `Sample Video.mp4`: Another sample video used for testing.
- `requirements.txt`: List of required dependencies.
- `LICENSE`: License information.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/amanmaner011/Camouflage-Detection.git
2. Navigate to the project directory:
   ```bash
   cd Camouflage-Detection/src
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage

1. Open `main.ipynb` and update the email and password fields:
    ```python
    from_email = "enter your email for sending mail"
    password = "16-digit password of that email generated by https://myaccount.google.com/apppasswords"
    ...
    to_email = "enter email address to receive the alert"

2. Execute the main script:
    ```bash
    python main.ipynb
