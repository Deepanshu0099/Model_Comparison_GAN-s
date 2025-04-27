# Model_Comparison_GAN-s
The project provides clear insights into how different GAN variants perform on the same dataset, making it ideal for academic study, benchmarking, or practical GAN experimentation.

This project presents a comprehensive comparison of three popular Generative Adversarial Network (GAN) architectures – LSGAN, WGAN, and WGAN-GP – using the MedMNIST (PathMNIST) dataset for medical image generation.

The aim is to explore how different loss functions and training strategies affect the quality, stability, and realism of generated images.

We train and evaluate each model under the same settings and visualize results through TensorBoard, while also reporting quantitative metrics including:

Inception Score (IS)

Fréchet Inception Distance (FID)

The project provides clear insights into how different GAN variants perform on the same dataset, making it ideal for academic study, benchmarking, or practical GAN experimentation.

Features Fully implemented LSGAN, WGAN, and WGAN-GP from scratch using PyTorch

 - TensorBoard integration for real-time image & metric comparison

 - Quantitative evaluation using IS and FID

 - Lightweight implementation optimized for MedMNIST dataset

 - Clean modular code structure with separate files for models, training, metrics, and visualizations

GAN-ASSIGNMENT/
│
├── lsgan.py            # LSGAN implementation
├── wgan.py             # WGAN implementation
├── wgan_gp.py          # WGAN-GP implementation
│
├── utils/
│   ├── metrics.py      # Metrics for IS and FID
│   └── visualize.py    # Image saving and TensorBoard image logging
│
├── datasets/
│   └── load_medmnist.py  # MedMNIST dataset loader
│
├── generated_images/   # Output sample images from each GAN


 Acknowledgements
MedMNIST: A Lightweight Benchmark for Medical Image Classification
TorchMetrics
Pytorch GAN Examples
