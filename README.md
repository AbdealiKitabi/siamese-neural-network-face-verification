# Siamese Neural Network for Face Verification

A computer vision project that uses a Siamese Neural Network to compare face images and determine whether they belong to the same person.

## Project Overview

This project explores deep learning–based face verification using a Siamese network architecture. It includes a Jupyter notebook for model development and training, along with a Python application for webcam-based face verification.

## Project Structure

.
├── app/
│   ├── faceid.py
│   └── Layers.py
├── CV Model.ipynb
├── .gitignore
└── README.md

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Jupyter Notebook
- Kivy

## Components

- **Model development:** Notebook containing the model-building and training workflow.
- **Custom layer:** `L1Dist.py` is not a separate file; the custom `L1Dist` layer is defined in `Layers.py`.
- **Face verification application:** `app/faceid.py` provides the application interface and webcam integration.

## Setup and Usage

Setup instructions and dependency versions will be added after the project environment and model-loading paths are finalized.

## Dataset and Model

The dataset, generated face images, training checkpoints, and trained model files are excluded from this repository because of their size and local/generated nature.

## Limitations

This repository is a work in progress. Installation instructions, reproducibility, model distribution, and evaluation results will be documented as they are verified.
