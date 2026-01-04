# Automating Port Operations

A machine learning project focused on automating maritime port operations through **image-based vessel classification**. The goal of this project is to reduce human error in identifying incoming vessels by leveraging deep learning models to classify boat types from images.

This work explores convolutional neural networks (CNNs) and transfer learning approaches to build an accurate and scalable classification system suitable for real-world port environments.

---

## Project Motivation

Manual vessel classification at ports is time-consuming and error-prone, especially under high traffic conditions. Misclassification can lead to operational inefficiencies, reporting errors, and safety concerns.

This project proposes an automated solution that:
- Identifies vessel types using image data
- Reduces bias and inconsistency from manual inspection
- Supports scalable and repeatable port monitoring workflows

---

### Description of Key Files

- **`Automating_Port_Operations_dataset/`**  
  Original labeled dataset used for training and evaluation.

- **`train_images/`**  
  Training image set organized by vessel class.

- **`test_images/`**  
  Held-out test images used for evaluation.

- **`main.ipynb`**  
  Primary notebook containing the final model pipeline, training, evaluation, and inference.

- **`autoportops.ipynb`**  
  Experimental notebook exploring model variations and preprocessing strategies.

- **`First Model Summary.docx`**  
  Documentation of the initial model design and results.

- **`Outputs.pdf`**  
  Visual outputs including accuracy plots, confusion matrices, and predictions.

- **`WriteUp.docx / WriteUp.pdf`**  
  Full project report covering motivation, methodology, experiments, and conclusions.

- **`source code.pdf`**  
  Archived source code and explanations.

---

## Methodology

This project applies deep learning techniques for image classification, including:

- Convolutional Neural Networks (CNNs)
- Transfer learning with pretrained models
- Image preprocessing and normalization
- Performance evaluation using accuracy and confusion matrices

Experiments compare different architectures and training configurations to identify a model suitable for deployment in operational environments.

---

## Results
Model performance, training curves, and classification results are documented in:
- Outputs.pdf
- WriteUp.pdf

These files provide detailed analysis and visual evidence of model effectiveness.
