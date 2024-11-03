# Passport Information Extraction using OCR

## Overview

This project utilizes Optical Character Recognition (OCR) to extract essential information from passport images. By leveraging the Doctr library and pre-trained OCR models, the application can identify and retrieve the document number, first name, last name, and expiration date from scanned passport images.

## Features

- **Document Number Extraction**: Identifies the passport document number by checking for patterns that include uppercase letters and digits.
- **Name Retrieval**: Extracts the first and last names based on their respective character lengths.
- **Expiration Date Detection**: Validates and retrieves the expiration date in the format DD/MM/YYYY using regular expressions.
- **Image Processing**: Supports various image formats for input and provides a visual output of recognized text.

## Requirements

- Python 3.x
- Doctr library
- TensorFlow and TensorFlow Addons
- Other required libraries can be installed via `pip`

## Installation

To set up the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/mindee/doctr.git
pip install -q typeguard>=4.0.1
pip install -q tensorflow-addons
pip install -qe doctr/.
pip install tf2onnx
pip install mplcursors
