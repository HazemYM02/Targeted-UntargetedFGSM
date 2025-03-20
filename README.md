# Targeted and Untargeted FGSM on CAPTCHA

This repository contains a Jupyter Notebook implementation of the **Fast Gradient Sign Method (FGSM)** for performing targeted and untargeted adversarial attacks on CAPTCHA images.

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Overview
Adversarial attacks are a significant concern in machine learning security. This project explores the effectiveness of FGSM in attacking CAPTCHA models by generating adversarial examples that either fool the model into misclassification (untargeted attack) or force it to predict a specific incorrect label (targeted attack).

## Requirements
Ensure you have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- TensorFlow/PyTorch
- NumPy
- Matplotlib
- OpenCV (cv2)

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/targeted-untargeted-fgsm-captcha.git
   cd targeted-untargeted-fgsm-captcha
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Start Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

## Usage
1. Open the Jupyter Notebook `target-un-targeted-fgsm-on-catcha.ipynb`.
2. Follow the provided cells to execute the FGSM attack.
3. Modify parameters such as the epsilon value to observe different attack strengths.

## Results
- The notebook visualizes adversarial examples and their effect on model predictions.
- Compares the accuracy drop due to untargeted and targeted FGSM attacks.
- Demonstrates the vulnerability of CAPTCHA models to adversarial perturbations.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---
Feel free to contribute by submitting issues or pull requests!

