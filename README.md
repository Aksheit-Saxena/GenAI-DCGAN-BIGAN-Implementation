# GenAI-DCGAN-BIGAN-Implementation

What are the problems the code solves?

1. Train a DC GAN on the given data with the usual GAN loss. Plot the loss curves for the Generator and Discriminator networks. Plot a 10 by 10 grid of images for generated images. Vary the number of times the generator and discriminator are trained and document the changes in the behaviour. Compute FID between 1000 real and generated images.

2.  Implement a Bi-GAN on the given dataset using Wasserstein’s loss. Plot 10 by 10 grids of generated images. Plot the generated images obtained via linear interpolation between a pair of latent vectors.
 Perform posterior inference using the trained generator on the real data and use the inferred latent in a linear and SVM classifier, to classify between the three data classes.


Dataset Used: https://www.kaggle.com/datasets/andrewmvd/animal-faces

Due to the large size of the code, it could not be added to the repo due to size restrictions. I have made the link available for the entire working code.Complete details of the code along with the results can be found in the jupyter notebook.


Please find the Jupyter notebook code at: https://drive.google.com/file/d/1mQ3i-GJ-p1kAMX4LMw6Hjj65D-t6fkUm/view?usp=sharing
