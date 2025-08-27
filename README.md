The notebook contains the prototype for th eautomatic mapping application for the Astrogea library.
The automatic mapping is performed by applying an undercomplete autoencoder architecture to a spectral parameters CRISM MTDR datacube.
The datacube undergoes some preprocessing steps, including the removal of unphysical signals and normalization by re-centering.
The hyperparameter optimization is performed by means of random search, over a large hyperparameter grid.
The network architecture found is made of a maximum monolayer encoder and a multi-hidden layer decoder. 
Before the altent space, a Gumbel Softmax activation function is applied, to enforce single latent space neuron activation.
The training is then performed with the hyperparameter set found in th eoptimization and the result is then showed for each latent space neuron.
