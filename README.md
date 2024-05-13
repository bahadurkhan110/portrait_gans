# Portrait GAN - Generate Realistic Portrait Images through Generative Adversarial Networks
<p align="center">
  <img src="image_at_epoch_0640.png" alt="Generated Portraits" width="600" height="400">
</p>

## Overview
This project aims to train Generative Adversarial Networks (GANs) to generate realistic portrait images. GANs are powerful deep learning models capable of generating synthetic data that closely resembles real data. In this project, we leverage GANs to generate diverse and visually appealing portrait images, which can have applications in art generation, data augmentation, and image synthesis.

## Features
- Trained  GAN models on a diverse portrait dataset.
- Used TensorFlow and Keras for implementation.
- Explored hyperparameter tuning, optimization strategies, and model architectures.

## Getting Started
1. Clone the repository:
   ```bash
     git clone https://github.com/bahadurkhan110/portrait_gans.git
   ```


## Dataset
The portrait dataset used in this project consists of diverse images of human faces sourced from various online repositories. The dataset is preprocessed and augmented to improve model generalization and diversity in generated images.


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Results

After extensive training and experimentation, the trained GAN models demonstrate promising results in generating realistic portrait images. Despite challenges such as mode collapsing and training instability, the models show gradual improvement over time, capturing essential features and patterns present in the dataset.


<p align="center">  
  <img src="results/image_at_epoch_0001.png" alt="Generated Portraits at Epoch 100" width="200" height="200">
  <img src="results/image_at_epoch_0100.png" alt="Generated Portraits at Epoch 100" width="200" height="200">
  <img src="results/image_at_epoch_0200.png" alt="Generated Portraits at Epoch 200" width="200" height="200">
  <img src="results/image_at_epoch_0300.png" alt="Generated Portraits at Epoch 300" width="200" height="200">
</p>
<p align="center">
  <img src="results/image_at_epoch_0400.png" alt="Generated Portraits at Epoch 400" width="200" height="200">
  <img src="results/image_at_epoch_0500.png" alt="Generated Portraits at Epoch 500" width="200" height="200">
  <img src="results/image_at_epoch_0600.png" alt="Generated Portraits at Epoch 600" width="200" height="200">
  <img src="results/image_at_epoch_0639.png" alt="Generated Portraits at Epoch 639 (Final Epoch)" width="200" height="200">
</p>

## Future Directions
- Explore advanced GAN architectures such as Progressive GANs or StyleGAN.
- Refine evaluation metrics and incorporate human perceptual studies for more comprehensive assessment.
- Investigate techniques for handling diverse and complex datasets to improve model performance.
- Experiment with transfer learning and fine-tuning on specific portrait styles or characteristics.

