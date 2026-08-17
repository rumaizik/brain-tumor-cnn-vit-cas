# Brain Tumor Classification Using CNN, Vision Transformer, and CAS

This project was done as part of our course modeling workshop. Our group worked on comparing two deep learning approaches for brain tumor MRI image classification:

- Convolutional Neural Network (CNN)
- Vision Transformer (ViT)

As an extension to the comparison, we also proposed our own idea called **CAS (Counterfactual Actuarial Swap)** as an innovation in the project.

## Project Overview

The main goal of this project is to classify brain MRI images into different tumor categories and compare the performance of CNN and Vision Transformer models.

We wanted to study how a traditional deep learning model like CNN performs compared to a transformer-based vision model. Along with that, we explored our own custom idea, CAS, to make the project more innovative and experimental.

## Dataset

We used the **Brain Tumor MRI Dataset** from Kaggle:

[Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

The dataset contains MRI images organized into the following classes:

- Glioma
- Meningioma
- Pituitary
- No Tumor

## Models Used

### 1. CNN
The CNN model is used as a baseline deep learning model for image classification. It learns spatial features through convolution and pooling layers.

### 2. Vision Transformer (ViT)
The Vision Transformer is a transformer-based model applied to image classification. It treats image patches like tokens and learns relationships using self-attention.

### 3. CAS
CAS stands for **Counterfactual Actuarial Swap**.

This is our project innovation. In simple terms, CAS is an experimental idea where we try to study model behavior by introducing controlled counterfactual changes and comparing how the system responds. It is not a standard benchmark model, but something we explored as a creative extension of the main CNN vs ViT comparison.

## Objective

The main objectives of this project are:

- to classify brain MRI images accurately
- to compare CNN and Vision Transformer performance
- to explore a custom innovation through CAS
- to understand how different architectures behave on medical image data

## Files in This Repository

This repository contains notebooks, notes, and supporting files related to our project work.

Some dataset folders are not uploaded here because of size limitations, but the code and project materials are included.

## Note

If a notebook preview does not render properly on GitHub, it can still be opened in:

- Google Colab
- Jupyter Notebook
- JupyterLab

## Conclusion

This project helped us understand both convolution-based and transformer-based approaches for medical image classification. It also gave us a chance to think beyond standard implementation by proposing CAS as our own extension.

Overall, this was both a comparative study and a small innovation-based exploration done as part of our course work.
