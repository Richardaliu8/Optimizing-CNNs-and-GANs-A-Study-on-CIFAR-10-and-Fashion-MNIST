# Optimizing-CNNs-and-GANs-A-Study-on-CIFAR-10-and-Fashion-MNIST  

Project Overview  

This project focuses on optimizing Convolutional Neural Networks (CNNs) and Generative Adversarial Networks (GANs) using the CIFAR-10 and Fashion-MNIST datasets. By incorporating batch normalization and leveraging TensorFlow, we aim to improve performance and stability, demonstrating significant enhancements in image classification and generation. This study highlights the potential of advanced deep learning techniques for better model accuracy and efficiency.

Features  
CNN Architecture Implementation: Developed a CNN with three convolutional layers using ReLU activation and softmax for classification. Batch normalization was added between layers to assess its effect on performance.  
GAN Development: Implemented a Vanilla GAN for the Fashion-MNIST dataset with batch normalization in the generator model to stabilize training and enhance image quality.  
Training and Evaluation: Trained the CNN on CIFAR-10 for 15 epochs with a batch size of 128, using the Adam optimizer and categorical cross-entropy loss function. Evaluated the GAN's ability to generate realistic images and addressed mode collapse issues.  
Performance Comparison: Compared training and validation loss, test accuracy, and error rates of models with and without batch normalization to highlight the impact on convergence and overfitting.  
Data Visualization: Plotted training loss, validation loss, and generated images to effectively communicate the results and improvements achieved.  

Purpose  
The purpose of this project is to leverage advanced deep learning techniques to enhance the performance and stability of CNNs and GANs for image classification and generation. By optimizing these models on the CIFAR-10 and Fashion-MNIST datasets, we aim to provide valuable insights into the effectiveness of batch normalization and other architectural improvements, assisting researchers and practitioners in developing more robust and accurate neural networks.  
