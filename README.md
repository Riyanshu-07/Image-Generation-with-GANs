# 🎨 From Noise to Faces: Custom Image GAN using PyTorch

> A Generative Adversarial Network (GAN) built from scratch using PyTorch to generate realistic human faces from random noise.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![Google Colab](https://img.shields.io/badge/Google%20Colab-GPU-orange)

---

## 🚀 Project Overview

Generative Adversarial Networks (GANs) are one of the most exciting developments in Deep Learning. Instead of simply analyzing data, GANs learn to create entirely new content.

This project trains two neural networks in an adversarial setting:

🎨 **Generator** → Creates synthetic images from random noise.

🕵️ **Discriminator** → Determines whether an image is real or generated.

Through this competitive learning process, the Generator gradually learns to produce increasingly realistic images.

---

## ✨ Key Features

✅ GAN implemented from scratch using PyTorch

✅ Custom Dataset & DataLoader Pipeline

✅ Adversarial Training Framework

✅ Synthetic Face Generation

✅ GPU-Accelerated Training with Google Colab

✅ Training Progress Visualization

---

## 📈 Training Progress

One of the most interesting aspects of this project is observing the model evolve:

| Epoch 1      | Epoch 50              |
| ------------ | --------------------- |
| Random Noise | Realistic Human Faces |

The Generator gradually learns meaningful visual patterns and produces increasingly realistic outputs.

---

## 🛠️ Tech Stack

| Technology   | Purpose                  |
| ------------ | ------------------------ |
| Python       | Core Programming         |
| PyTorch      | Deep Learning Framework  |
| Torchvision  | Image Processing         |
| NumPy        | Numerical Computation    |
| Matplotlib   | Visualization            |
| Google Colab | GPU Training Environment |

---

## 📂 Project Structure

```text
Image-Generation-with-GANs/
│
├── vanillaGAN.ipynb
├── README.md
└── .gitignore
```

## ⚙️ Installation

```bash
git clone https://github.com/Riyanshu-07/Image-Generation-with-GANs.git

cd Image-Generation-with-GANs

pip install torch torchvision numpy matplotlib pillow
```

## ▶️ Run the Project

Open the notebook:

```bash
jupyter notebook vanillaGAN.ipynb
```

Run all cells to:

* Load and preprocess images
* Train the GAN
* Monitor Generator & Discriminator losses
* Generate synthetic images
* Visualize training progress

---

## 🎯 What I Learned

This project helped me gain practical experience in:

🔹 Generative Adversarial Networks (GANs)

🔹 Deep Learning using PyTorch

🔹 Image Synthesis & Generation

🔹 Dataset Preprocessing

🔹 Neural Network Training & Optimization

🔹 GPU-Based Training Workflows

---

## 🔮 Future Improvements

* [ ] Implement DCGAN Architecture
* [ ] Experiment with WGAN-GP
* [ ] Improve Image Quality & Resolution
* [ ] Add Model Checkpointing
* [ ] Build a Web-Based Demo

---

## 👨‍💻 Author

### Riyanshu Kandwal

AI/ML Enthusiast | Deep Learning Explorer | Open Source Contributor

🔗 GitHub: https://github.com/Riyanshu-07

---

⭐ If you found this project interesting, consider starring the repository and sharing your feedback!
