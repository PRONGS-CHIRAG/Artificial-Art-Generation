# Artifcial Art Generation
 
## Overview

This project implements the Neural Style Transfer algorithm introduced by Gatys et al. (2015), which combines the content of one image with the artistic style of another to create novel artworks. Built using TensorFlow and the VGG19 network, this Jupyter notebook provides an end-to-end solution for generating stylized images through deep learning.
## Key Features

    VGG19 Architecture: Leverages pre-trained VGG19 for feature extraction

    Style & Content Blending: Preserves content structure while transferring artistic style

    Customizable Parameters: Control style/content weighting and iteration count

    Visualization Tools: Integrated matplotlib plotting for progress tracking

    Transfer Learning: Utilizes ImageNet-trained weights for optimal feature recognition

## Requirements

Ensure you have the following dependencies installed:

```bash
pip install tensorflow numpy pandas matplotlib scipy PIL 
```

## Usage

### 1. Clone the Repository

```bash
git clone <repository_url>
cd <repository>
```

### 2. Run Jupyter Notebook

Execute the notebook to train and evaluate the model:

```bash
jupyter notebook Art_Generation_with_Neural_Style_Transfer.ipynb
```
