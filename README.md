# CAPTCHA Solver with CNN

This project demonstrates a complete deep learning workflow to break 5-character CAPTCHA images by:

- Generating a large synthetic dataset of CAPTCHA images using various fonts
- Building a multi-output convolutional neural network (CNN) to predict each character independently
- Training and validating the model on generated datasets
- Decoding model predictions into readable CAPTCHA strings
- Testing the model on new CAPTCHA images

---

## Features

- **Synthetic Data Generation**: Automatically create thousands of labeled CAPTCHA images using random alphanumeric sequences and a variety of fonts.
- **Multi-Output CNN**: Design a CNN with multiple output layers to predict each character in the CAPTCHA separately.
- **End-to-End Pipeline**: From data generation, loading, preprocessing, model building, training, and testing.
- **TensorFlow & Keras**: Uses modern TensorFlow APIs and Keras functional model for clarity and flexibility.

---

## Getting Started

### Prerequisites

- Python 3.6+
- TensorFlow 2.x
- Pillow
- NumPy

Install dependencies with:

```bash
pip install tensorflow pillow numpy
