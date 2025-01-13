# Neural Network Experimentation on MNIST Dataset

## Overview
This project is a deep learning experiment focused on understanding how different neural network configurations perform on the MNIST handwritten digits dataset. The main focus is on comparing various optimization techniques, activation functions, and hidden layer configurations to identify which setups yield the best results.

## Dataset
The MNIST dataset is a collection of 70,000 handwritten digit images categorized into 10 classes (0-9). Each image is a 28x28 pixel grayscale image. The dataset is widely used for training and testing in the field of machine learning.

## Key Experimentation Areas
1. **Optimization Techniques**: Comparison between Stochastic Gradient Descent (SGD) and Mini-batch Gradient Descent.
2. **Activation Functions**: Analysis of ReLU and tanh functions in terms of their impact on test accuracy over epochs.
3. **Hidden Layer Neurons**: Evaluation of test accuracy with varying numbers of neurons in the hidden layers.

## Repository Contents
- **`Neural Network Experimentation on MNIST Dataset.ipynb`**: Jupyter notebook containing the code, experimentation, and analysis.
- **`Report_ Neural Network Experimentation on MNIST Dataset.pdf`**: Detailed report documenting the findings and insights.
- **`Accuracy Comparison - SGD vs Mini-batch SGD.png`**: Visualization comparing the accuracy of different optimization techniques.
- **`ReLU vs tanh Test Accuracy Over Epochs.png`**: Graph showing the test accuracy for different activation functions over training epochs.
- **`Test Accuracy vs Hidden Layer Neurons.png`**: Plot analyzing the impact of hidden layer neuron count on test accuracy.

## How to Run the Project
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/Neural_Network_Experimentation_MNIST.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Neural_Network_Experimentation_MNIST
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook "Neural Network Experimentation on MNIST Dataset.ipynb"
    ```
4. Run the cells in the notebook to view the results and plots.

## Results and Observations
- **SGD vs. Mini-batch SGD**: Mini-batch SGD showed faster convergence and better test accuracy compared to standard SGD.
- **ReLU vs. tanh Activation**: ReLU achieved higher accuracy and convergence speed in comparison to tanh.
- **Hidden Layer Neurons**: Increasing the number of neurons up to a certain limit improved accuracy, but too many neurons led to overfitting.

## Conclusion
This project provides insights into how different configurations can impact the performance of neural networks on the MNIST dataset. Understanding these variations is crucial for building more effective deep learning models.

## References
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- Various Deep Learning Optimization Techniques

## Author
**Gaurav Bharatavalli** - [LinkedIn](https://www.linkedin.com/in/gaurav-b-r/) - [GitHub](https://github.com/Gaurav-B-R/)

Feel free to reach out if you have any questions or suggestions!
