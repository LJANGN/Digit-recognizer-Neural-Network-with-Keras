# Digit-recognizer-Neural-Network-with-Keras
This is a deep neural network model for identifying images of handwritten digits. The model is first trained with a set of 42000 images and then tested against a set of 28000 images. It was my first submission to the competition Digit Recognizer on kaggle.com (https://www.kaggle.com/c/digit-recognizer). The accuracy of the final model was closer to 98%. 

The data is taken from the MNIST dataset ("Modified National Institute of Standards and Technology"), which is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.
