## Day 44 - Autoencoders

- This code defines a simple autoencoder using TensorFlow and Keras for the purpose of reconstructing images. It uses a neural network architecture with one hidden layer of 128 units, with ReLU activation for encoding and a final layer of 784 units with a sigmoid activation for decoding.

- The code demonstrates the training of the autoencoder using the MNIST dataset, which is loaded, preprocessed, and used for training and validation. The autoencoder is trained for 50 epochs with a batch size of 256.

- After training, the code visualizes the original and reconstructed images using matplotlib, displaying a side-by-side comparison of the input images and their corresponding reconstructed versions. This helps assess the performance of the autoencoder in image reconstruction.