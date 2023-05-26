# kaggle_bird_classifier

## Description

This project is related to the Kaggle competition [100-bird-species](https://www.kaggle.com/datasets/gpiosenka/100-bird-species). The objective of the competition is to build a CNN (Convolutional Neural Network) for accurately classifying 15 selected bird species. In this project, we leverage [transfer learning](https://keras.io/guides/transfer_learning/), specifically using the [MobileNetV2](https://keras.io/api/applications/mobilenet/) model as the base model, to construct the CNN.

The CNN achieved an average accuracy of 95% on the test data, demonstrating the effectiveness of transfer learning in image classification. Additionally, the model achieved a perfect accuracy of 100% on a small validation set. This project serves as a showcase of how transfer learning can enhance the performance of a CNN in the task of bird species classification.

## Table of Contents

- [Project Name](#project-name)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributions](#contributions)

## Installation

To use the code in this repository, please follow these steps:

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/CMonnin/kaggle_bird_classifier.git
   ```
2 Change directory
   ```bash
   cd kaggle_bird_classifier
   ```
3. Install the required dependencies using:

   ```bash
   pip install -r requirements.txt
   ```
4. Download the data from [100-bird-species](https://www.kaggle.com/datasets/gpiosenka/100-bird-species) (approx. 2 GB). Extract the data and store it in a directory kaggle_bird_classifier/kaggle/archive/

## Usage
Please follow the notebook found [here](https://github.com/CMonnin/kaggle_bird_classifier/blob/main/bird_classifier.ipynb) to see how the model was trained, tested, and validated  

## Contributions
The following people contributed to this project:  
[https://github.com/Franck816](https://github.com/Franck816)  
[https://github.com/sqossain](https://github.com/sqossain)  
[https://github.com/Anshuboom](https://github.com/Anshuboom)  
[https://github.com/CMonnin](https://github.com/CMonnin)  
