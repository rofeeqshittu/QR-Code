# QR Code Generator and Reader

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A simple GUI application using PyQt6 to generate and read QR codes. The application allows users to load images, generate QR codes from text, save generated QR codes, and read QR codes from loaded images.
![app_gui.png](app gui pic)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Python script creates a graphical user interface (GUI) application for generating and reading QR codes. It leverages PyQt6 for the GUI and utilizes the qrcode library for QR code generation and the OpenCV library for QR code reading.

## Features

- Load images to the GUI for processing.
- Generate QR codes from provided text.
- Save generated QR codes as PNG images.
- Read QR codes from loaded images.

## Getting Started

### Prerequisites

Before running the application, ensure you have the following installed:

- Python 3
- PyQt6
- OpenCV (`cv2`)
- qrcode library

Install the required libraries using the following:

```bash
pip install PyQt6 opencv-python qrcode[pil]
```

### Installation

1. Clone the repository:

```bash
git clone https://github.com/rofeeqshittu/qr-code.git
cd qr-code
```

2. Run the application:

```bash
python app.py
```

## Usage

1. Launch the application.
2. Use the "Load" option to open an image.
3. Click "Generate Code" to create a QR code from the provided text in the text area.
4. Save the generated QR code using the "Save" option.
5. Use the "Read Code" button to read QR codes from the loaded image.

## Contributing

Feel free to contribute to this project. If you have suggestions, find bugs, or want to add features, please do...

## License

Free for all to use..


------ ©️R Rofeeq Shittu 2023. - https://github.coom/rofeeqshittu/qr-code.git -----
