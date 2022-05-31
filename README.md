# MNIST_handwritten_digits_classification
# CS182008 Sarfaraz Ahmed 7A
MNIST hand written digit classification using keras.

These are the following experiments that were performed on the **Assignment1_DeepLearning_7A** file.

## **Experiments:**
1) **swapping** the activation functions at hidden and output layer: accuracy and loss was just messed up.

2) Not using an activation function on the hidden layer: affected the accuracy with -0.08 and loss increased from 0.1864 to 0.2638.

3) Using activation function **relu**: loss: 0.0806 - accuracy: 0.9788.

4) Changing the activation function from relu to tanh: test loss was 0.0772 and test accuracy was 0.9781. Loss nearly decreased 1%.

5) Changing the activation function to sigmoid: loss: 0.0769 - accuracy: 0.9764.

6) Using 5 epochs instead of 10: did not affect the accuracy that much, but loss was decreased from 0,9788 to 0.1138.

7) Changing optimizer from adam to RMSProp: loss increased from 0.0806 to 0.0849 and accuracy was 0.977.

## **Model Accuracy (using 5 epochs):**

![model_accuract](https://user-images.githubusercontent.com/69521378/171150611-d92c3b60-4a7a-42fe-82ff-d63731bb06a3.png)
