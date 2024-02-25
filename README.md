# Automated Number Plate Recognition Project

This project demonstrates an automated approach to recognizing text on vehicle number plates using Python and OpenCV. The process involves several steps, from image preprocessing, including color space conversions and contour detection, to masking number plates and extracting text using EasyOCR. This README provides a step-by-step guide on how the project works and how to set it up and run it on your own machine.
### output image
![output_3](https://github.com/Hasanshovon/Python-ANPR-with-OpenCV-and-EasyOCR-/assets/26182608/b381d6eb-d9bf-4e0f-a2e2-b014866f6bf1)

## Project Workflow

The project is divided into distinct steps, each crucial for the successful extraction of text from number plates:

1. **Reading and Visualizing Images**: Utilizing OpenCV to load and display images for preprocessing.
2. **Applying Color Shifts and Changes**: Adjusting image colors, such as converting to grayscale and changing from BGR to RGB color spaces, to enhance text detection.
3. **Detecting Contours**: Employing OpenCV's `findContours` method to identify potential number plates within images.
4. **Masking Number Plates**: Isolating the number plate area to improve OCR accuracy by minimizing background noise.
5. **Extracting Number Plate Text**: Using EasyOCR to recognize and extract text from the masked number plate areas.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.6 or newer
- Pip (Python package installer)

