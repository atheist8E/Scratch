Diffusion Model

0. Reference
   - https://medium.com/geekculture/variational-autoencoder-vae-9b8ce5475f68 
   - https://deepinsight.tistory.com/127
   - https://github.com/hwalsuklee/tensorflow-mnist-VAE
   - https://ratsgo.github.io/generative%20model/2017/12/19/vi/
   - https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf
   - https://pub.towardsai.net/diffusion-models-vs-gans-vs-vaes-comparison-of-deep-generative-models-67ab93e0d9ae
   - https://ffighting.net/deep-learning-paper-review/diffusion-model/diffusion-model-basic

2. History
   2.1 Auto Encoder
      - [Idea] Manifold Learning / Reconstruction Loss
      - [Usage] Dimension Reduction / Anomaly Detection
      - [Limit] Not Generative Model
     
   2.2 Variation Auto Encoder
      - [Idea] Variational Inference (True Posterior <-> Approximated Posterior by Encoder) / Generation from Latent Vector / Reparameterization Trick
      - [Usage] Generation / Data Interpretation through Latent Space
      - [Limit] Low-fidelity of Generated Instance (Inter-Class Overlap on Latent Space & Pixel-based Loss)
     
   2.3 Generative Adversarial Network
      - [Idea] 
    
4. Concept
   - Forward Process
   - Reverse Process

5. Detail
   - Equation
   - Loss Function

6. Implementation
   - U-Net
   - Time Embedding
