 Debre Berhan University 
 Department of Computer Science

 
 Group Assignment for Selected Topics in Computer Science (CoSc4132)
 
 Handwritten Digit Recognition Using CNN 

##  Group Members
1. Ebrahim Abdulwehab  -------- DBUE/0728/13
2. Afewerk Alemu       -------- DBUE/0702/13
3. Kefelegn Habtamu    -------- DBUE/0862/13
4. Bitaniya Getye      -------- DBUE/0718/13
5. Tsegaye Wondesen    -------- DBUE/0787/13


## Project Overview
This project implements a CNN model trained on the MNIST dataset to classify handwritten digits (0–9). It includes a Gradio-based web interface for real-time digit prediction and serves as a foundational model for future applications in livestock identification systems.


## Why We Chose This Topic
Our team selected handwritten digit recognition because:

- It provides a clean, well-established starting point for learning CNNs and transfer learning.
- The MNIST dataset is ideal for demonstrating model development, training, evaluation, and deployment.
- Most importantly, this project serves as the foundation for our upcoming final-year project: **"Rule-Based Sheep Breeding Expert System"**
    Real sheep farms rely on **ear-tag numbers** for identification. These tags often contain handwritten or printed digits. Our goal is to extend this project by:
        - Collecting sheep ear-tag images  
        - Retraining or fine-tuning this CNN model  
        - Integrating automatic tag recognition into the expert system  
        This creates a seamless pipeline where image recognition supports rule-based reasoning — a strong, innovative          combination.

## Tech Stack
- Language: Python 3.7+
- Libraries: TensorFlow, Keras, NumPy, Matplotlib, Gradio
- Interface: Gradio Web UI
- Dataset: MNIST (70,000 labeled digit images)

## Features
- CNN architecture using TensorFlow/Keras  
- 98–99% accuracy on MNIST dataset  
- Gradio web interface for real-time predictions  
- Clean, modular code ready for future domain-specific fine-tuning  
- Transfer-learning-friendly design

## Installation
- Clone the repository
git clone https://github.com/EBRO-MAN/Handwritten-digit-recognition-CNN-.git
cd Handwritten-digit-recognition-CNN-

## The CNN model includes:
- Input Layer: 28x28 grayscale image
- Convolutional Layers: 2 layers with ReLU activation
- Pooling Layers: MaxPooling2D
- Dropout: To prevent overfitting
- Dense Layers: Fully connected layers with softmax output

## Project Structure
Handwritten-digit-recognition-CNN-/
│
├── train_model.ipynb       # google colab for training and evaluation
└── README.md               # Project documentation


##  Future Work
- Collect sheep ear-tag digit images
- Fine-tune the model using transfer learning
- Integrate with a rule-based expert system for sheep breeding
- Deploy as a web application for use
  
## Acknowledgment
We express our sincere gratitude to our course instructor Mr. Betselot Y. for providing clear instruction, and an opportunity to work on a real-world deep learning problem that strengthens our understanding of modern AI systems.


**We appreciate your time reviewing our project and welcome all feedback.**
