CNN 
Fashion MNIST

A Convolutional Neural Network (CNN) implemented completely from scratch using Python and NumPy without using deep learning frameworks like TensorFlow or PyTorch for model building.

This project demonstrates the fundamental working of CNNs including:

* Convolution Layer
* Forward Propagation
* Backpropagation
* Flatten Layer
* Fully Connected Layer
* Softmax Activation
* Training and Evaluation

The model is trained on the Fashion MNIST dataset for image classification.

Project Objective

The objective of this project is to understand the internal working of Convolutional Neural Networks by manually implementing the major components of CNN architecture.


##Dataset Used: Fashion MNIST
Fashion MNIST contains:
* 70,000 grayscale images
* 10 clothing categories
* Image size: 28 × 28 pixels

Classes include:
* T-shirt/top
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle boot

Technologies Used
* Python
* NumPy
* TensorFlow/Keras (only for dataset loading)

# Model Accuracy
The CNN model achieved approximately:
 75.50% Accuracy on the Fashion MNIST test dataset.


# How to Run

## 1. Install Dependencies
pip install numpy tensorflow

## 2. Run the Program
python cnn_from_scratch.py

# Sample Output

```text
Training Started...

Epoch: 1
Loss: 1.1913

Epoch: 2
Loss: 0.6903

Epoch: 3
Loss: 0.5411

Final Accuracy:  75.50%

## Limitations

This implementation is simplified for educational purposes:

* MaxPool backward propagation not implemented
* No ReLU activation
* No batch optimization
* Slower than framework-based CNNs


#  Conclusion

This project demonstrates how a CNN can be built from basic principles using only NumPy. It provides a deeper understanding of how modern deep learning models process images and learn patterns through convolution and backpropagation.
