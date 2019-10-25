# Generative_adversarial_networks


This codes is borrowed from the TensorFlow tutorial on Generative Adversarial Networks

Generative Adversarial Networks (GANs) are one of the most interesting ideas in computer science today. 
Two models are trained simultaneously by an adversarial process. A generator ("the artist") learns to 
create images that look real, while a discriminator ("the art critic") learns to tell real images apart from fakes.

During training, the generator progressively becomes better at creating images that look real, 
while the discriminator becomes better at telling them apart. The process reaches equilibrium when the discriminator can 
no longer distinguish real images from fakes.

A second diagram of a generator and discriminator

This notebook demonstrates this process on the Fashion-MNIST data-set. 
