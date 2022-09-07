# Latent Dynamical Models - Imbizo 2022


We consider a latent dynamical model to extract a (low dimensional) structure underlying the (high dimensional) neural activity. 
Goal:
- fit a sequence of neural activity data to infer the latent variables that generate this data and the dynamics with which the latents evolve

Implementation:
- apply the Expectation Maximisation algorithm with the assumptions of linear dynamics in the latent space and Gaussian noise in the projection from latent variables to the neural activity space
