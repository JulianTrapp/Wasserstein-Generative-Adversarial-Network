# Wasserstein-Generative-Adversarial-Network
In this Machine Learning Exam I created two types of Generative Adversarial Networks (GANs) with different loss functions. The aim of the two networks is to train the generator network to generate samples from a given probability distribution in a way that the discriminator cannot distinguish it from real samples. In this example I worked with data from a 2D Ising Model which is one of the most successful and broadly applicable models in statistical physics.  

The 2D-Ising Model for a ferromagnet describes the system as a grid of spins in discrete states up (+1) or down (-1) and in this case only considers nearest neighbour interaction between the spins. This simplifies the Hamiltonian of the system a lot. Still it is by far not trivial to calculate the partition sum of the system because the number of spin configurations scales exponentially with the number of sites ~2^N. 

The aim of the following code is to train a neural network in order to be able to sample from the thermal equilibrium distribution of the Ising System using a Generative Adversarial Network (GAN).    
