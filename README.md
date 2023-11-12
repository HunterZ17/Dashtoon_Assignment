# Dashtoon_Assignment
In this kernel, we’ll implement the style transfer method that is outlined in the paper, Image Style Transfer Using Convolutional Neural Networks, by Gatys in PyTorch.
In the presented research, style transfer is implemented utilizing the features extracted from the 19-layer VGG Network. This network consists of a sequence of convolutional and pooling layers, along with a small number of fully-connected layers. The convolutional layers are organized into stacks, and their order within each stack is crucial. For instance, Conv_1_1 denotes the initial convolutional layer through which an image is processed in the first stack, while Conv_2_1 represents the first convolutional layer in the second stack. The most profound convolutional layer in the entire network is labeled as conv_5_4. The architecture thus involves a hierarchical arrangement of convolutional layers, each contributing to the overall style transfer process.


This README file provides instructions on setting up and running the notebook for the project. Follow the steps below to ensure a smooth setup process.

Before you begin, make sure you have the following installed on your system:

- [Git](https://git-scm.com/)
- [Python](https://www.python.org/downloads/) (version 3.x recommended)
- [Jupyter Notebook](https://jupyter.org/install)

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/HunterZ17/Dashtoon_Assignment.git
   
2. The following Python packages are required to run the notebook:
   pytorch and matplotlib
