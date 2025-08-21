# Multi-Language Handwritten Text Recognition

This project aims to build a Deep Learning-based system for:
- Recognizing handwritten text in multiple languages
- Translating text into other languages
- Providing accessibility output (TTS, Braille) for visually impaired users

## Project Structure
HTR-Accessibility/
│── data/ # datasets (IAM, Hindi, etc.)
│── notebooks/ # Jupyter notebooks for experiments
│── src/ # source code
│ ├── preprocessing/ # image preprocessing scripts
│ ├── models/ # deep learning models (CRNN, Transformers, etc.)
│ ├── translation/ # translation module integration
│ ├── accessibility/ # TTS and Braille conversion
│ └── utils/ # helper functions
│── requirements.txt # dependencies
│── README.md # project overview

## Setup
```bash
pip install -r requirements.txt
