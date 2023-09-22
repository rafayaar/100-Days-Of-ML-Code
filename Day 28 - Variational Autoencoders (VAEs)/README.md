## Day 28 - Variational Autoencoders (VAEs)
- This code shows basic implementation of Variational Autoencoders on MNIST fashion dataset 
- The train_step method in this VAE class is responsible for performing a single training step. It calculates the reconstruction loss and the Kullback-Leibler (KL) divergence loss, combining them to form the total loss used for gradient descent optimization.
- This VAE implementation assumes a binary cross-entropy loss for the reconstruction loss and uses the reparameterization trick for sampling latent variables.s