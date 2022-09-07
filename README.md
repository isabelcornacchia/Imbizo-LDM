# Latent Dynamical Models - Imbizo 2022

![](/latent_LDS.png)

We consider a latent dynamical model to extract a (low dimensional) structure z underlying the (high dimensional) neural activity x. 

Goal:
- fit a sequence of neural activity data to infer the latent variables that generate this data and the dynamics with which the latents evolve
- compare the fit when the data is generated with Gaussian noise or with Poisson noise

Implementation:
- generate two synthetic datasets from a *true* latent model, one with Gaussian observation noise and one with Poisson noise
- apply the Expectation Maximisation algorithm on X with the assumptions of *linear dynamics* in the latent space and *Gaussian noise* in the projection from latent variables to the neural activity space
- compare the fit of the two models
