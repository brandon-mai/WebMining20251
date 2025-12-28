## Web Mining Project 20251 - Link Prediction

### Introduction

This project investigates two novel approaches for the Link Prediction problem: **Efficient Link Prediction with Hashing (ELPH)** and **Refined Graph Auto-Encoder (Refined GAE)**. Our goal is to evaluate and compare the performance and efficiency of these methods.

### Methods

### Efficient Link Prediction with Hashing (ELPH)
ELPH is a scalable Graph Neural Network model that improves link prediction by using hashing to sketch subgraphs. It captures structural information efficiently without the high computational cost associated with traditional subgraph-based methods.

*   **Paper**: [Graph Neural Networks for Link Prediction with Subgraph Sketching](https://openreview.net/pdf?id=m1oqEOAozQU)
*   **Source Code for our experiments**: https://github.com/brandon-mai/subgraph-sketching

### Refined GAE
Refined GAE demonstrates that a standard Graph Auto-Encoder, when properly tuned and enhanced with simple strategies (like Edge Masking and PULL loss), can achieve state-of-the-art performance, challenging the need for more complex architectures.

*   **Paper**: [Reconsidering the Performance of GAE in Link Prediction](https://arxiv.org/html/2411.03845v4)
*   **Source Code for our experiments**: https://github.com/brandon-mai/Refined-GAE

### Experiments

We provide two comprehensive notebooks that handle the entire workflow, including environment setup and executing experiment commands. These notebooks remain friendly for both **Google Colab** and **Kaggle** environments.

*   **`elph_experiments.ipynb`**: Includes the setup and commands to run experiments for the ELPH method.
*   **`refined_gae_experiments.ipynb`**: Includes the setup and commands to run experiments for the Refined GAE method.

To run the experiments, simply open the notebooks in your preferred platform and execute the cells.
