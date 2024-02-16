# PixelWise: Leveraging Convolutional Neural Networks for Handwritten Digit Classification
In our endeavor, we are tackling the challenge of classifying handwritten digits present in the MNIST dataset. Our objective is to develop a machine learning algorithm capable of accurately identifying and categorizing these handwritten numbers. This entails providing the algorithm with a handwritten digit as input and enabling it to successfully determine the corresponding numerical value. Focusing on the MNIST dataset, we are determined to harness the power of Convolutional Neural Networks (CNNs) and Vision Transformers (ViT) to push the boundaries of accuracy and efficiency.

# MNIST DATASET
The MNIST database is a collection of 70,000 handwritten digits, split into a training set of 60,000 and a test set of 10,000 examples, derived from a mix of U.S. Census Bureau employees and high school students.  These monochrome images are size-normalized and centered in a 28x28 pixel frame, with the original images processed to preserve aspect ratio within a 20x20 pixel box, resulting in grey levels due to anti-aliasing. 

The MNIST database is a key resource for training and testing in the field of machine learning, specifically for developing algorithms in computer vision. Its widespread use and simplicity make it an initial benchmark for evaluating the performance of new models, particularly in digit recognition tasks.

The original MNIST dataset already comes pre-split into training and testing sets using tensorflow. Our code utilizes the provided split-

Training set: Contains 60,000 images and their corresponding labels for training the model.

Testing set: Contains 10,000 images and their corresponding labels for evaluating the model's performance after training.

# Understanding Image Classification
Image classification is a fundamental task in computer vision that involves categorizing images into predefined classes or labels. In today's digital era, this capability finds widespread applications across various domains. One such application is the recognition of handwritten digits, a cornerstone task in fields ranging from digit recognition in postal services to automated form processing in finance and healthcare.

# The Role of CNNs and ViT
Both CNNs and ViT offer distinct advantages in addressing the challenges of image classification. CNNs, with their hierarchical structure and ability to capture spatial information through convolutional layers, have long been the go-to choice for tasks like this. Their success lies in their ability to automatically learn features from the data, making them particularly effective for tasks where the input data has a grid-like topology, such as images.On the other hand, Vision Transformers have emerged as a promising alternative, leveraging self-attention mechanisms to capture global dependencies in images without relying on convolutional operations. This allows ViT to effectively model long-range interactions, making them particularly suited for tasks where global context is crucial, such as understanding relationships between different parts of an image.
