# cifar10-cnn-autoencoder
1) Description:
   This project implements a CNN-based autoencoder to denoise images from the CIFAR-10 dataset, effectively reconstructing clean images from noisy inputs.

2) Key Features:
  Autoencoder Architecture: Utilizes convolutional layers for feature extraction and reconstruction, incorporating max pooling and upsampling layers.
  Data Preprocessing: Adds Gaussian noise to images to create a noisy dataset, enhancing the model's robustness.
  Training Configuration: Trained for 10 epochs with the Adam optimizer and Mean Squared Error (MSE) as the loss function.
  Performance: Achieved a final training loss of 0.0052 and a validation loss of 0.0051, demonstrating effective denoising capabilities.

3) Programming Tools: 
  Python, NumPy, TensorFlow, Matplotlib.
