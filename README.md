# Advanced Image Editor Using Python

## Description

This Advanced Image Editor is a simple yet powerful tool built using Python, OpenCV, and NumPy. It allows users to apply various filters and image processing techniques to their images through a graphical user interface. The application is designed for both educational purposes and practical use cases, providing a clear demonstration of basic image processing operations.

## Features

- **Gaussian Filter**: Smoothens the image using a Gaussian kernel.
- **High Pass Filter**: Enhances the edges in the image.
- **Histogram Equalization**: Improves the contrast of the image.
- **Contour Detection**: Detects and draws contours in the image.
- **Gaussian Noise Addition**: Adds Gaussian noise to the image.
- **Mean Filter**: Applies a mean filter to the image.
- **Low Pass Filter**: Smoothens the image using a low pass filter.
- **Min-Max Smoothing**: Applies min-max smoothing to the image.
- **Median Filter**: Applies a median filter to the image.
- **Hybrid Median Filter**: Applies a hybrid median filter to the image.
- **Morphological Operations**: Performs dilate, erode, open, and close operations on the image.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- SciPy
- PyQt5

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/devcom33/Advanced-Image-Editor-Using-Python.git
    cd Advanced-Image-Editor-Using-Python
    ```

2. **Create and activate a virtual environment (optional but recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate    # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the GUI application:**

    ```bash
    python ui_app.py
    ```

2. **Load an image:**
    - Click on `File` -> `Open` and select the image you want to edit.

3. **Apply filters:**
    - Use the toolbar and menu options to apply various edits and effects to your image.

4. **Save the image:**
    - Click on `File` -> `Save` to save your edited image.

## Directory Structure
'''
Advanced-Image-Editor-Using-Python/
├── README.md
├── requirements.txt
├── filter_image.py
├── ui_app.py
'''
