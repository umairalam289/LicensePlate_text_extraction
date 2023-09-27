# License Plate Detection and Text Extraction

This repository contains a Jupyter Notebook that demonstrates the process of detecting license plates in images and extracting text from them using a combination of YOLO for object detection and Tesseract for Optical Character Recognition (OCR).

## Overview

- **License Plate Detection**: Utilizes the YOLO (You Only Look Once) model to detect license plates in images.
- **Text Extraction**: Once the license plates are detected, the Tesseract OCR engine is used to extract text from the detected plates.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- OpenCV
- PyTesseract
- Ultralytics YOLO
- PIL
- Matplotlib
- Numpy

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the repository directory and install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open the provided notebook and run the cells to detect license plates and extract text.

## Results

The notebook processes a set of images, detects license plates, and extracts text from them. The results are visualized in the notebook itself.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
