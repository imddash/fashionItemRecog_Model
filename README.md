**🧥 Fashion MNIST CNN Classifier**

This project demonstrates a Convolutional Neural Network (CNN) built using TensorFlow and Keras to classify images from the Fashion MNIST dataset, which consists of 28x28 grayscale images of 10 different clothing categories.

**Project Overview:**
 
The objective is to build a deep learning model that can recognize and classify fashion products into categories such as shirts, trousers, bags, etc., using CNNs.

**🧠 Model Architecture**:

The model uses the following architecture:

Conv2D: 32 filters, 3x3 kernel, ReLU activation

MaxPooling2D

Conv2D: 64 filters, 3x3 kernel, ReLU activation

MaxPooling2D

Conv2D: 128 filters, 3x3 kernel, ReLU activation

MaxPooling2D

Flatten

Dense: 10 output classes with softmax activation

**🧪 How to Run
Prerequisites**

-> Python 3.x

-> TensorFlow

-> NumPy

-> Matplotlib

-> scikit-learn

Installation:

pip install tensorflow numpy matplotlib scikit-learn

Run the Script:

python fashion_mnist_cnn.py


📜 License

This project is open-source and available under the MIT License.
