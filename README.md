# Digit Recognition using Keras
> A classic problem in the field of pattern recognition is that of handwritten digit recognition. Suppose that you have images of handwritten digits ranging from 0-9 written by various people in boxes of a specific size - similar to the application forms in banks and universities.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

The goal is to develop a model that can correctly identify the digit (between 0-9) written in an image.

- What is the background of your project?

Objective: To develop a model using Keras which should correctly classify the handwritten digits from 0-9 based on the pixel values given as features. Thus, this is a 10-class classification problem.

- Business Problem Statement:

In this project, trying to experiment with Keras for digit-recognition using Keras.

- What is the dataset that is being used?

For this problem, we use the MNIST data which is a large database of handwritten digits. The 'pixel values' of each digit (image) comprise the features, and the actual number between 0-9 is the label.

Since each image is of 28 x 28 pixels, and each pixel forms a feature, there are 784 features. MNIST digit recognition is a well-studied problem in the ML community, and people have trained numerous models (Neural Networks, SVMs, boosted trees etc.) achieving error rates as low as 0.23% (i.e. accuracy = 99.77%, with a convolutional neural network). Before the popularity of neural networks, though, models such as SVMs and boosted trees were the state-of-the-art in such problems.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- In this project, trying to experiment with Keras for digit recognition problem. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.6.9
- Numpy - version 1.21.5
- Pandas - version 1.3.5
- Seaborn - version 0.11.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad.
- This project was based on Upgrad's Tutorial.


## Contact
Created by [@shrutipandit707] - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->