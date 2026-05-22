
# GAN Architecture & Variants Implementation using PyTorch

[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains robust implementations of Generative Adversarial Networks (GANs) and their popular variants using PyTorch. This codebase has been utilized as core training material for **Faculty and Student Training Programs** across prestigious institutions, including:
* NIT Warangal
* NIT Nagpur
* NIT Hamirpur
* LNMIIT Jaipur
* SVNIT Surat
* PP Savani University, Surat

---

## 📌 Overview

Generative Adversarial Networks (GANs) are a class of machine learning frameworks where two neural networks (a Generator and a Discriminator) contest with each other in a zero-sum game, leading to the generation of high-quality synthetic data. This repository serves as a practical guide to understanding and implementing these architectures from scratch.

---

## 🚀 Implementations Included

### 1. Basic GAN (Vanilla GAN)
* Standard implementation featuring fully connected generator and discriminator networks.
* **Supported Datasets:** MNIST, FashionMNIST, and CIFAR-10.

### 2. Deep Convolutional GAN (DCGAN)
* Uses spatial convolutional layers in the Discriminator and convolutional-transpose layers in the Generator.
* Implements architectural topologies and batch normalization practices for stable image generation.

### 3. Least Squares GAN (LSGAN)
* Replaces the traditional cross-entropy loss with a least-squares loss function.
* Minimizes the objective function to tackle the vanishing gradient problem and improve image quality.

### 4. Conditional GAN (CGAN)
* An extension of the standard GAN framework where both the generator and discriminator are conditioned on class labels.
* Enables targeted, controlled generation of specific data classes.

---

## 🛠️ Requirements & Setup

Ensure you have Python 3.7+ and the following dependencies installed:

* PyTorch $\ge$ 1.8
* torchvision
* NumPy
* Matplotlib
* tqdm (for progress bars)
* TensorBoard (Optional, for training visualization)

## Installation


git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name
pip install -r requirements.txt

## 📖 External Resources & Talks

For more insights on advanced deep learning topics, explore the official portfolios below:

* **About the Author:** [Dr. Praveen Kumar Chandaliya Portfolio](https://sites.google.com/aid.svnit.ac.in/drpraveenkumarchandaliya/about?authuser=1)
* **Invited Talks & Seminars:** [Explainable AI, Transformers, and Deep Learning Talks](https://sites.google.com/aid.svnit.ac.in/drpraveenkumarchandaliya/talks?authuser=1)

---

## 🔬 Featured Research: Face Age Progression and Regression

If you find this repository or the associated research useful in your academic work, please consider citing the following papers focusing on Face Aging, Rejuvenation, and Generative Modeling:

```bibtex
@inproceedings{PraveenICD2022,
  title={ChildGAN: Face aging and rejuvenation to find missing children},
  author={Praveen Kumar Chandaliya and Neeta Nain},
  booktitle={Pattern Recognition},
  year={2022},
  volume={129},
  pages={108761}
}

@inproceedings{PraveenICB2019,
  title={Conditional Perceptual Adversarial Variational Autoencoder for Age Progression and Regression on Child Face},
  author={Praveen Kumar Chandaliya and Neeta Nain},
  booktitle={International Conference on Biometrics (ICB)},
  year={2019},
  pages={1-8}
}

@inproceedings{PraveenSAMSP2021,
  title={Child Face Age Progression and Regression using Multi-Scale Patch GAN},
  author={Praveen Kumar Chandaliya and Neeta Nain},
  booktitle={International Joint Conference on Biometrics (IJCB)},
  year={2021},
  pages={1-8}
}

@article{AWGAN2022,
  title={AWGAN: Face Age Progression and Regression using Attention},
  author={Praveen Kumar Chandaliya and Neeta Nain},
  journal={Neural Computing and Applications},
  year={2022},
  volume={34},
  pages={1-16}
}
