
# Dog Denoiser

A Jupyter Notebook–based deep learning project to remove noise from dog images using convolutional autoencoders.

## Project Structure
- `Dog_Denoiser.ipynb` – Main notebook for training and evaluating the denoising autoencoder.
- `models/` – Directory containing saved model weights.
- `data/` – Directory for datasets, including noisy and clean dog images.
- `utils/` – Utility scripts for data preprocessing and visualization.

## Installation
```bash
git clone https://github.com/RanjithaNarasimhamurthy
cd Dog-Denoiser
```

## Usage
1. Ensure your dataset is placed in the `data/` directory, organized into `noisy/` and `clean/` subfolders.
2. Launch the notebook:
   ```bash
   jupyter notebook Dog_Denoiser.ipynb
   ```
3. Follow the notebook steps to:
   - Load and preprocess images.
   - Build and train the convolutional autoencoder.
   - Evaluate denoising performance and visualize results.

## Dependencies
- Python 3.8+
- TensorFlow or PyTorch
- numpy
- pandas
- matplotlib
- OpenCV
- scikit-image

## Results
The autoencoder effectively reduces noise from dog images, achieving clear reconstructions. Feel free to tweak network architecture and hyperparameters for improved performance.

