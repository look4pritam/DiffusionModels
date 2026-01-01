# Diffusion Models

## Variational Autoencoders
- Encoder + Decoder
- Latent space
- Selection from latent space

## Concept
- Forward Diffusion
  - Add (Gaussian) noise
  - Number of time steps
  - Markov chain - The future depends only on the present state, and not on the past history.
- Reverse Diffusion
  - Start with random noise
  - Remove noise
  - Reconstruct clear image  
  - How ?
    - Convolutional Neural Network
    - UNet
    - Time step t
    - Predict noise at time step t
    - Subtract noise from noisy image to get clear image
- Conditional Diffusion
  - Guided Diffusion
  - Conditioned on text prompts
  - How ?
    - Text prompts
    - Text embeddings
    - Condition - Image and image captions pairs
         
## References
- [YouTube - Diffusion Models for AI Image Generation](https://www.youtube.com/watch?v=x2GRE-RzmD8)
- [YouTube - Diffusion Models Just Beat Large Language Models?](https://www.youtube.com/watch?v=Yu4ZWy1GjlE)

