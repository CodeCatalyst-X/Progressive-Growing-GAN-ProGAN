# Progressive Growing GAN (ProGAN) — TensorFlow From Scratch

A from-scratch TensorFlow implementation of Progressive Growing GAN (ProGAN) based on the original paper
“Progressive Growing of GANs for Improved Quality, Stability, and Variation” (Karras et al.)

This project focuses on clarity, correctness, and research-level understanding, avoiding heavy abstractions and frameworks so the core ideas of ProGAN are fully transparent.

## 📌 Overview

Training GANs directly at high resolutions is unstable. ProGAN addresses this by progressively growing the Generator and Discriminator, starting from very low resolutions (4×4) and smoothly increasing to higher resolutions using fade-in transitions.

This repository demonstrates how to implement that idea step by step in TensorFlow.

<br>

## 🧠 Key Features

- Progressive resolution growth (4×4 → higher resolutions)

- Generator and Discriminator built from scratch

- Fade-in (alpha blending) mechanism

- Stable GAN training loop in TensorFlow

- Modular, readable code suitable for learning and research

