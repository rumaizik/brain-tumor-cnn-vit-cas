# Brain Tumor Classification Using CNN, Vision Transformer, and CAS

This project was done as part of our course modeling workshop. Our group worked on comparing two deep learning approaches for brain tumor MRI image classification:

- Convolutional Neural Network (CNN)
- Vision Transformer (ViT)

As an extension to the comparison, we also introduced our own idea called **CAS (Counterfactual Actuarial Swap)** as a small innovation in the project.

## Project Overview

The aim of this project is to classify brain MRI images into different categories and compare how CNN and Vision Transformer perform on the same task.

Instead of only building one model, we wanted to do a proper comparison between a traditional deep learning method and a transformer-based method. After that, we extended the work with CAS to make the project more exploratory and innovative.

## Dataset

We used the **Brain Tumor MRI Dataset** from Kaggle:

[Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

The dataset contains MRI images grouped into four classes:

- Glioma
- Meningioma
- Pituitary
- No Tumor

## Working Flow

The overall workflow of our project is:

1. Collect the brain MRI dataset from Kaggle.
2. Organize the dataset into training and testing folders.
3. Preprocess the images so they can be given to the models.
4. Train the CNN model on the dataset.
5. Train the Vision Transformer model on the same dataset.
6. Compare both models using accuracy and overall performance.
7. Apply CAS as an experimental extension to study model behavior in a different way.
8. Analyze the outputs and compare the final results.

## Models Used

### 1. CNN
The CNN model is used as a baseline model for image classification. It captures image features through convolution, activation, and pooling operations.

### 2. Vision Transformer (ViT)
The Vision Transformer is a transformer-based architecture for computer vision. It divides an image into patches and processes them using self-attention.

### 3. CAS
CAS stands for **Counterfactual Actuarial Swap**.

This is our proposed innovation in the project. The idea behind CAS is to explore how the model behaves when counterfactual or altered feature relationships are introduced. It is not a standard model from the dataset source, but an experimental concept we added as part of our group work.

## Objective

The main objectives of this project are:

- to classify brain MRI images correctly
- to compare CNN and Vision Transformer performance
- to explore a custom innovation through CAS
- to understand how different architectures behave on medical image data

## Expected Output

From this project, we aim to observe:

- classification performance of CNN
- classification performance of ViT
- comparison between both models
- the effect of CAS as an experimental extension

## Files in This Repository

This repository includes notebooks, notes, and supporting project files.

Due to file-size limitations, the full dataset is not uploaded here, but the project-related files are available.

## Note

If a notebook preview does not render properly on GitHub, it can still be opened using:

- Google Colab
- Jupyter Notebook
- JupyterLab

## Conclusion

This project helped us understand both convolution-based and transformer-based methods for medical image classification. It also gave us a chance to go beyond direct comparison by adding CAS as our own extension.

Overall, this project is a combination of implementation, comparison, and innovation as part of our coursework.
