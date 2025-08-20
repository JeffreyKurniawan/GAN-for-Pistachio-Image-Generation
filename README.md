# GAN-for-Pistachio-Image-Generation
Generative Adversarial Networks (GANs) to generate realistic pistachio images. 

## 📌 Project Overview  
This project explores the use of **Generative Adversarial Networks (GANs)** to generate realistic pistachio images. Built with **TensorFlow/Keras**, the model was trained on a pistachio image dataset to synthesize new samples.  

We experimented with both **baseline** and **customized generator architectures**, aiming to enhance the **realism and diversity** of the generated images. Model performance was measured using the **Frechet Inception Distance (FID)** metric.  

---

## 🏗️ GAN Architecture  

- **Generator**  
  - Transposed Convolutional Layers  
  - Batch Normalization  
  - ReLU Activation  

- **Discriminator**  
  - Convolutional Neural Network (CNN)  
  - LeakyReLU Activation  
  - Dropout Regularization  

- **Training Setup**  
  - Loss Function: **Binary Crossentropy**  
  - Optimizers: Adam for both networks  
  - Evaluation Metric: **FID Score**  

---

## 🎯 Key Highlights  
- Successfully generated synthetic pistachio images from random noise.  
- Compared baseline vs. modified generator design for quality improvement.  
- Used **FID** to quantify realism and fidelity of generated images.  

---
