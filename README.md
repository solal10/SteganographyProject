# SteganographyProject
Copyright © 2017, Robin David - MIT-Licensed
This project is a modified version of the [LSB-Steganography](https://github.com/RobinDavid/LSB-Steganography) project by Robin David. It includes additional features and improvements to enhance the steganography functionalities.

## Overview

Steganography is the practice of hiding information within other non-secret text or data. This project provides a method to hide and extract messages within images using the Least Significant Bit (LSB) technique.

## Features

- Hide messages within images
- Extract hidden messages from images
- Support for various image formats
- Enhanced user interface

## Requirements

- Python 3.x
- PIL (Pillow)
- NumPy

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/SteganographyProject.git
   cd SteganographyProject

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3.Install the required packages:
   ```bash
   pip install -r requirements.txt
```




## Usage
Encoding (Hiding a Message)
To hide a message within an image, use the following command:

### Encoding (Hiding a Message)
```bash
python encode.py -i input_image.png -o output_image.png -m "Your hidden message here"
```
-i: Path to the input image where the message will be hidden.

-o: Path to the output image that will contain the hidden message.

-m: The message you want to hide within the image.

### Decoding (Extracting a Message)
To extract a hidden message from an image, use the following command:

```bash
python decode.py -i input_image.png
```
-i: Path to the input image from which the hidden message will be extracted.
