
# Qualitative analysis of AI-Powered Face Generation 

## Project Overview

This project analyzes the performance of various generative models in computer vision, including **Variational Autoencoders (VAEs)**, **Generative Adversarial Networks (GANs)**, and state-of-the-art **Stable Diffusion models**. The goal is to evaluate the image generation quality and the impact of manipulation techniques such as prompt interpolation and diffusion noise variations.

### Datasets Used:
- **CelebA**: Used for training VAEs.
- **CIFAR-10**: Used for training Diffusion models.
- **CelebA-HQ**: Used for training Stable Diffusion models.

### Key Investigations:
- Investigated the impact of **prompt manipulation** and **noise variation** on image generation quality.
- Evaluated the **generated image variations** resulting from different methods.

### Results:
- **GANs**: Generate sharp images but are challenging to train and offer limited control over the output.
- **VAEs**: Provide interpretable models but generate blurry images.
- **Diffusion Models** (especially Stable Diffusion): Generate the most realistic faces due to efficient use of low-dimensional latent space, text conditioning support, and flexibility in semantic control.

## Files in the Project

1. **UNET Diffusion.ipynb**: A standard diffusion model implementation using **U-Net** architecture.
2. **Stable Diffusion.ipynb**: Unconditioned Stable Diffusion model (no text prompts used alongside the images).
3. **Text Conditioned Stable Diffusion.ipynb**: A conditional Stable Diffusion model that includes text prompts to condition the generated output.
4. **VAE.ipynb**: Implementation of **Variational Autoencoder** for image generation.

## Conclusion

Through this project, we have compared the generative abilities of different models (GANs, VAEs, Stable Diffusion), showing that while GANs and VAEs have their strengths, **Stable Diffusion** models, especially with **text conditioning**, produce the most realistic and high-quality images.
