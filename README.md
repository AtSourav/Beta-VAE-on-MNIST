# Beta-VAE-on-MNIST

Building and training a beta VAE on the MNIST dataset and comparing the effect of different beta values.

There are three notebooks with titles suggestive of parameter values. The two notebooks with beta=1 (with latent dim 2 and 10) work on resized (14x14) images, while the one with varying beta values and latent dim 12 works on the original MNIST images. The experiments in this third notebook seem to sugges that the best overall results (reconstruction and generation of new images) are obtained with beta values between 1 and 3, while better reconstruction is ofc obtained when low values of beta are used to suppress the kl term. 


