
 # Adversarial Robustness Assignment

This repository contains implementations of **adversarial attacks and model inversion attacks** using the **Adversarial Robustness Toolbox (ART)** and **PyTorch**.

The goal of this assignment is to explore how machine learning models can be attacked and how sensitive information can be reconstructed from trained models.

---

## Tasks Implemented

### 1. Evasion Attacks (ℓ∞ Norm)

The following adversarial attacks were implemented:

- FGSM (Fast Gradient Sign Method)
- PGD (Projected Gradient Descent)
- Targeted PGD Attack

For each attack:
- Adversarial images were generated
- Predicted classes were evaluated
- Misclassification rates were calculated

---

### 2. ℓ2 Norm Attack

Implemented attack:

- PGD Attack with ℓ2 constraint

Evaluation included:

- Adversarial image generation
- Prediction analysis
- Misclassification rate

---

### 3. Model Inversion Attack – AT&T Face Dataset

The **MIFace model inversion attack** from the **Adversarial Robustness Toolbox** was used to reconstruct training samples.

Dataset used:

- AT&T Faces Dataset (ORL Faces)

Goal:

- Demonstrate how a trained model can leak information about the training data.

Output:

- Reconstructed face images from the trained classifier.

---

### 4. Model Inversion Attack – CIFAR-10

A CNN model was trained on the **CIFAR-10 dataset**, and a **model inversion attack** was applied.

Steps:

1. Load CIFAR-10 dataset
2. Train CNN classifier
3. Apply model inversion attack
4. Visualize reconstructed images

---

## Technologies Used

- Python
- PyTorch
- Adversarial Robustness Toolbox (ART)
- NumPy
- Matplotlib
- Scikit-learn

---

## Repository Structure

