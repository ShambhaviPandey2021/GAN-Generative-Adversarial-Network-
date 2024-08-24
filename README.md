# GAN - Generative Adversarial Network for Celebrity Face Generation

Welcome to the GAN - Generative Adversarial Network repository! This project focuses on generating realistic celebrity faces using deep learning techniques, specifically through the implementation of GANs.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Generative Adversarial Networks (GANs) are a class of machine learning frameworks designed by Ian Goodfellow and his colleagues in 2014. The goal of this project is to leverage GANs to create high-quality, synthetic images of celebrity faces. By training the model on a dataset of celebrity images, the GAN learns to generate new images that resemble the real ones.

## Features

- Generate high-resolution celebrity faces.(It is suppose to generate high resolution but couldn't do )
- Easy-to-use training and inference scripts.
- Modular architecture for easy customization.
- Visualize training progress and generated images.

## Getting Started

### Prerequisites

To run this project, you need to have the following installed:

- Python 3.7 or later
- TensorFlow or PyTorch(I used Pytorch)
- Other required Python libraries (listed in `requirements.txt`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ShambhaviPandey2021/GAN-Generative-Adversarial-Network.git
Navigate to the project directory:

bash
Copy code
cd GAN-Generative-Adversarial-Network
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Usage
Prepare your dataset of celebrity images and place it in the designated folder.

Train the GAN model:

bash
Copy code
python train.py --dataset path_to_your_dataset
Generate new celebrity faces after training:

bash
Copy code
python generate.py --model path_to_trained_model
Requirements
Python 3.7+
TensorFlow 2.x or PyTorch
Numpy
Matplotlib
Other libraries as listed in requirements.txt
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

License
This project is licensed under the MIT License - see the LICENSE file for details.
