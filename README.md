# Deep Neural Networks for Radon Transform and Inverse Radon Reconstruction

## Overview
This project explores the use of deep neural networks, specifically Convolutional Neural Networks (CNNs), to perform inverse Radon transformations for 2D image processing. The goal is to enhance image reconstruction quality compared to traditional methods like Filtered Back Projection (FBP), particularly in noisy or incomplete data scenarios.

## Features
- Implements Radon Transform to convert 2D images into sinograms.
- Designs a CNN-based approach to perform inverse Radon transform.
- Compares deep learning-based reconstruction with traditional methods.
- Evaluates performance using metrics like MSE and SSIM.
- Potential applications in medical imaging, seismic imaging, and non-destructive testing.

## Colab Notebook
Run the project in Google Colab:
[Google Colab Link](https://colab.research.google.com/drive/1sLeYY8wmJ9_BOyu81I6JphxGDXCWTA7s?usp=drive_link)

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository_link>
   cd <repository_name>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:
   ```bash
   python main.py
   ```

## Usage
- **Training**: Modify `config.py` to adjust model parameters, then execute `train.py`.
- **Evaluation**: Use `evaluate.py` to analyze model performance on test data.
- **Visualization**: View sinograms and reconstructed images using `visualize.py`.

## Results
- The CNN model provides improved reconstruction quality, especially for noisy or incomplete sinograms.
- The deep learning-based approach outperforms traditional FBP in terms of noise robustness and accuracy.
- Once trained, the model can reconstruct images in real-time, making it suitable for real-world applications.

## Future Work
- Extending to 3D Radon transforms.
- Enhancing reconstruction quality for sparse data.
- Applying the model to real-world medical and industrial datasets.

## License
This project is released under the MIT License.
