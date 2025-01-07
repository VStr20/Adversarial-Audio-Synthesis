# Adversarial Audio Synthesis

This repository explores adversarial approaches to audio synthesis using GAN-based models. It includes two primary implementations, **PianoGAN** and **SpectoGAN**, designed for generating audio representations such as piano music or spectrogram-based audio synthesis.

## Features
- **PianoGAN**: A GAN model tailored for generating piano music.
- **SpectoGAN**: A GAN model for generating audio through spectrogram representations.
- Interactive Jupyter notebooks for model exploration and experimentation.
- Supplementary reports and a demo video showcasing the results.

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Structure](#structure)
- [Examples](#examples)
- [References](#references)
- [License](#license)

## Requirements
The project requires the following libraries and frameworks:
- Python 3.8+
- PyTorch
- NumPy
- Matplotlib
- librosa
- Jupyter Notebook


```bash
git clone https://github.com/VStr20/Adversarial-Audio-Synthesis.git
cd Adversarial-Audio-Synthesis

Adversarial-Audio-Synthesis/
│
├── PianoGAN.ipynb                 # Notebook for PianoGAN implementation
├── SpectoGAN.ipynb                # Notebook for SpectoGAN implementation
├── pianogan.py                    # Script for PianoGAN
├── spectogan.py                   # Script for SpectoGAN
├── Adversarial-Audio-Synthesis.pdf  # Main project documentation
├── Report_PianoGAN_SpectoGAN.pdf  # Detailed report on both models
├── video.mp4                      # Demo video showcasing results
└── README.md                      # Project documentation

## Usage

### PianoGAN
- Open the `PianoGAN.ipynb` notebook.
- Follow the instructions to preprocess data, train the model, and generate piano audio samples.

### SpectoGAN
- Open the `SpectoGAN.ipynb` notebook.
- Use the notebook to train and generate audio from spectrograms.

### Python Scripts
For command-line execution, use the corresponding Python scripts:
- `pianogan.py` for PianoGAN training and generation.
- `spectogan.py` for SpectoGAN.

