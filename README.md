# Introduction: Artificial Neural Networks

Artificial neural networks (ANNs) are modeled after how the brain processes information. ANNs employ nodes to handle data in the same way as neurons in the brain receive, analyze, and transmit signals. These nodes process inputs using weights, biases, and activation functions to generate outputs.

ANNs are organized as:

The input layer feeds raw data into the network.
The Hidden Layers that transform the data to reveal patterns.
The output layer provides the ultimate forecast or outcome.
The basic perceptron solves linear problems by computing a weighted sum of inputs and applying an activation function.
However, for more difficult jobs, multi-layer networks with nonlinear capabilities are required. These sophisticated networks serve as the foundation for current deep learning, effectively addressing difficulties like as image recognition and language processing.

# Project Setup and Deployment

This article explains how to set up and execute the project on your own system. Basic programming skills, particularly in Python, are recommended. If you're new to Python, start by learning the fundamentals. The tutorial also covers how to deploy the project in real-world systems, providing a smooth transition from development to operation.

# Requirements

What things do you need to install the software and how to install them

Anaconda Navigator: To create and manage the Python environment.
Git: For cloning and managing the repository.
Dataset: The data required to train and test the neural network.

## Installation 

1. Visit Anaconda's official website-https://www.anaconda.com/download/success and download the installer for your operating system.
2. Install Anaconda by following the on-screen instructions.
3. Once installed, open Anaconda Navigator and launch Jupyter Notebook from the interface. Alternatively, search for "Jupyter Notebook" directly on your system and open it.

## How to Run the Project

1.First clone the repository by open your command prompt in Windows or Mac/Linux.
Use the git clone command to download the project files to your computer.
2.A folder will be created on your system with all the project files.
3.Then Open Jupyter Notebook and follow the steps below:
  a. Launch Jupyter Notebook via Anaconda Navigator or search for it directly.
  b. Navigate to the folder where you saved the project files.
  c. Open the 100931720-DATA1200-Assignment4.ipynb file to start running the code.
4. After that Run the Code by following the steps below:
  a. Click on a code cell in the notebook.
  b. Press Shift + Enter or click the Run button in the toolbar.
  c. Repeat this for all cells in order.
  
# Explanation of the code

## Installing required libraries:
To install the essential libraries, use pip.

## Neural Network Classifier:
The model use MLPClassifier with the following settings:
hidden_layer_sizes=(5, 4, 5): This defines the network's layers.
Activation='relu': Speeds up training by avoiding the vanishing gradient issue.
solver='adam': Automatically changes the learning rate with minimum adjustment.
max_iter=10000: Sets the model to run for up to 10,000 iterations before stopping if it converges.
Random_state=100: Controls the production of random numbers, ensuring consistent outcomes.
The model's performance is assessed using:

## Confusion Matrix: 
compares expected and actual values.

## Classification Report:
Displays critical parameters such as precision, recall, and F1 score.

## Decision Tree:
Use DecisionTreeClassifier with random_state=100 to achieve consistent results. The model's performance is further assessed using the confusion matrix and classification report.

# Contribution

Community contributions are highly valued and play a key role in improving this project. Follow these straightforward steps to get started:

1. Fork the Repository: Create your own copy of the project to work on.
2. Create a New Branch: Start a new branch for your changes to keep the main branch stable.
3. Make Changes: Edit the code, documentation, or other project elements to add value.
4. Test Your Work: Ensure your updates are functional and error-free.
5. Submit a Pull Request (PR): Once satisfied, create a pull request with a clear explanation of your contributions.

Your feedback can help develop and enhance the project. 

# Version

This project adheres to Semantic Versioning (SemVer) principles to manage changes.

# Author

*  **Jayaprasanna** 

# License Information

MIT License is authorised to this project - [LICENSE.md](LICENSE.md)

# Acknowledgment

* Prof.Rejoy James, DATA 1202-03 Data Analysis Tools Analytics
