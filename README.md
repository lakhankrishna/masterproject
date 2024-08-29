# Super Resolution of Satellite Images using Transformer Learning

## Introduction

The main goal of this project is to build a more sophisticated model to enhance the clarity of satellite images. This is achieved through a fusion transformer architecture combined with Global Pixel Hybrid Attention algorithms. The proposed approach aims to improve the spatial resolution of low-resolution images, making them more accurate for applications such as environmental monitoring, urban planning, and disaster management. This advancement is expected to push the boundaries of current super-resolution methods in remote sensing.

## Aim

The primary objective of this project is to enhance the spatial resolution of satellite images using a fusion transformer architecture paired with Global Pixel Hybrid Attention techniques.

## Research Questions

- **RQ1**: How effective is the fusion transformer architecture with Global Pixel Hybrid Attention in improving the spatial resolution and detail level of satellite images compared to traditional super-resolution methods?
- **RQ2**: Which features and processes within the Global Pixel Hybrid Attention framework have the most significant impact on the super-resolution performance of satellite images?

## Methodology

The project leverages a combination of fusion transformer architecture and Global Pixel Hybrid Attention to upscale satellite images. The process involves several key steps:

1. **Data Preprocessing**: Loading and preparing satellite images for training and validation.
2. **Model Design**: Developing the fusion transformer architecture integrated with Global Pixel Hybrid Attention.
3. **Training**: Training the model using the preprocessed dataset to learn how to enhance image resolution.
4. **Evaluation**: Assessing the model's performance using metrics such as PSNR (Peak Signal-to-Noise Ratio) and SSIM (Structural Similarity Index).

## Libraries Used

- Python
- TensorFlow
- Keras
- OpenCV
- Matplotlib
- NumPy
- Pillow (PIL)
- Keras Tuner

## Inputs and Outputs of the model
1. The model takes inputs as lower resolution images of satellite
2. The model give ouput as image with higher resolution

## How to Run the Code

1. **Clone the repository**:
   ```bash
https://github.com/lakhankrishna/masterproject
2. Install anaconda with python 3.11
3. Open jupyter notebook
4. Go to cloned location on the computer
5. Open the Codefinal file 
6. Run the file