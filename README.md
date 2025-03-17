# 🐱🐶 Taming Overfitting in Deep Learning: A PyTorch Cat-Dog Classifier Guide

![Cat vs Dog Banner](https://img.shields.io/badge/PyTorch-v2.0-orange) ![License](https://img.shields.io/badge/License-MIT-blue) ![Status](https://img.shields.io/badge/Status-Complete-green)

Welcome to my journey of building a **Cat-Dog Classifier** using PyTorch – and more importantly, beating the overfitting beast! In this project, I turned a memorizing model into a generalizing champ using simple yet powerful techniques. Ready to dive into the world of CNNs, Dropout, and Data Augmentation? Let’s go! 🚀

---

## 🎯 What’s This All About?

Overfitting is every data scientist’s nightmare – your model aces the training data but flops on anything new. I faced this while training a CNN to classify cats and dogs from the Kaggle dataset (25,000 images). The solution? A mix of **Dropout** and **Data Augmentation** that took my validation accuracy from a measly **70%** to a solid **82%**. This guide (and code!) shows you how.

---

## ✨ Key Highlights

- **Base Model**: A simple CNN built with PyTorch – great at training (95%), terrible at validating (70%).
- **Dropout Magic**: Added a 50% dropout layer, shrinking the train-val gap.
- **Data Augmentation**: Flipped, rotated, and tweaked images to make the model smarter.
- **Results**: Balanced accuracy (83% train, 82% val) – no more overfitting!

Check out the [blog](#) for the full story – less code, more techniques!

---

## 🛠️ Tech Stack

| **Category**       | **Tools**                     |
|---------------------|-------------------------------|
| **Language**       | Python                       |
| **Framework**      | PyTorch                      |
| **ML Concepts**    | CNN, Dropout, Data Augmentation |
| **Data**           | Kaggle Cats vs. Dogs Dataset |

---

## 📊 Results at a Glance

| **Stage**             | **Train Accuracy** | **Val Accuracy** |
|-----------------------|--------------------|------------------|
| Base Model            | 97%               | 80%             |
| Dropout + Augmentation| 84%               | 83%             |

*Overfitting tamed, mission accomplished!*

---
