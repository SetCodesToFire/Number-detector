# Number-detector

## A Multilayer Convolutional Neural Network for the MNIST data
MNIST is a simple computer vision dataset. It consists of images of handwritten digits.



# Steps Involved
## 1) Loading MNIST DATASET into the project
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning.It was created by "re-mixing" the samples from NIST's original dataset. The creators felt that since NIST's training dataset was taken from American Census Bureau employees, while the testing dataset was taken from American high school students, it was not well-suited for machine learning experiments. Furthermore, the black and white images from NIST were normalized to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.

The MNIST database contains 60,000 training images and 10,000 testing images. Half of the training set and half of the test set were taken from NIST's training dataset, while the other half of the training set and the other half of the test set were taken from NIST's testing dataset. There have been a number of scientific papers on attempts to achieve the lowest error rate; one paper, using a hierarchical system of convolutional neural networks, manages to get an error rate on the MNIST database of 0.23 percent. The original creators of the database keep a list of some of the methods tested on it. In their original paper, they use a support vector machine to get an error rate of 0.8 percent. An extended dataset similar to MNIST called EMNIST has been published in 2017, which contains 240,000 training images, and 40,000 testing images of handwritten digits.

## 2)Starting the tensorflow interactive session
Importing the tensorflow into the project as well as creating a new tensorflow session.

## 3)Build a Multilayer Convolutional Network
## Weight Initialization
## Convolution and Pooling
## First Convolutional Layer
## Second Convolutional Layer
## Densely Connected Layer
## Dropout
## Output Layer

## 4)Training and Evaluating Model

step 0, training accuracy 0.2
step 100, training accuracy 0.82
step 200, training accuracy 0.82
step 300, training accuracy 0.94
step 400, training accuracy 0.86
step 500, training accuracy 0.94
step 600, training accuracy 1
step 700, training accuracy 0.96
step 800, training accuracy 0.94
step 900, training accuracy 0.94
step 1000, training accuracy 0.98
step 1100, training accuracy 1
step 1200, training accuracy 0.96
step 1300, training accuracy 1
step 1400, training accuracy 0.98
step 1500, training accuracy 0.98
step 1600, training accuracy 0.96
step 1700, training accuracy 0.98
step 1800, training accuracy 0.96
step 1900, training accuracy 0.98
step 2000, training accuracy 0.98
step 2100, training accuracy 1
step 2200, training accuracy 0.96
step 2300, training accuracy 1
step 2400, training accuracy 1
step 2500, training accuracy 0.96
step 2600, training accuracy 0.98
step 2700, training accuracy 0.98
step 2800, training accuracy 0.98
step 2900, training accuracy 1
step 3000, training accuracy 1
step 3100, training accuracy 0.92
step 3200, training accuracy 1
step 3300, training accuracy 0.96
step 3400, training accuracy 0.92
step 3500, training accuracy 0.98
step 3600, training accuracy 0.98
step 3700, training accuracy 1
step 3800, training accuracy 0.96
step 3900, training accuracy 1
step 4000, training accuracy 0.98
step 4100, training accuracy 1
step 4200, training accuracy 1
step 4300, training accuracy 0.98
step 4400, training accuracy 1
step 4500, training accuracy 0.94
step 4600, training accuracy 1
step 4700, training accuracy 0.98
step 4800, training accuracy 1
step 4900, training accuracy 0.98
step 5000, training accuracy 0.98
step 5100, training accuracy 1
step 5200, training accuracy 0.98
step 5300, training accuracy 1
step 5400, training accuracy 0.96
step 5500, training accuracy 1
step 5600, training accuracy 1
step 5700, training accuracy 1
step 5800, training accuracy 1
step 5900, training accuracy 1
step 6000, training accuracy 1
step 6100, training accuracy 0.96
step 6200, training accuracy 1
step 6300, training accuracy 1
step 6400, training accuracy 1
step 6500, training accuracy 1
step 6600, training accuracy 1
step 6700, training accuracy 1
step 6800, training accuracy 1
step 6900, training accuracy 1
step 7000, training accuracy 1
step 7100, training accuracy 1
step 7200, training accuracy 0.98
step 7300, training accuracy 1
step 7400, training accuracy 1
step 7500, training accuracy 1
step 7600, training accuracy 1
step 7700, training accuracy 0.98
step 7800, training accuracy 0.98
step 7900, training accuracy 1
step 8000, training accuracy 1
step 8100, training accuracy 1
step 8200, training accuracy 0.98
step 8300, training accuracy 1
step 8400, training accuracy 1
step 8500, training accuracy 1
step 8600, training accuracy 0.98
step 8700, training accuracy 0.98
step 8800, training accuracy 1
step 8900, training accuracy 1
step 9000, training accuracy 1
step 9100, training accuracy 1
step 9200, training accuracy 1
step 9300, training accuracy 1
step 9400, training accuracy 0.98
step 9500, training accuracy 1
step 9600, training accuracy 1
step 9700, training accuracy 1
step 9800, training accuracy 0.98
step 9900, training accuracy 0.98
step 10000, training accuracy 1
step 10100, training accuracy 0.98
step 10200, training accuracy 1
step 10300, training accuracy 1
step 10400, training accuracy 0.96
step 10500, training accuracy 0.98
step 10600, training accuracy 0.98
step 10700, training accuracy 1
step 10800, training accuracy 1
step 10900, training accuracy 1
step 11000, training accuracy 1
step 11100, training accuracy 1
step 11200, training accuracy 1
step 11300, training accuracy 1
step 11400, training accuracy 1
step 11500, training accuracy 1
step 11600, training accuracy 1
step 11700, training accuracy 1
step 11800, training accuracy 1
step 11900, training accuracy 1
step 12000, training accuracy 0.98
step 12100, training accuracy 1
step 12200, training accuracy 1
step 12300, training accuracy 1
step 12400, training accuracy 1
step 12500, training accuracy 1
step 12600, training accuracy 1
step 12700, training accuracy 1
step 12800, training accuracy 1
step 12900, training accuracy 1
step 13000, training accuracy 1
step 13100, training accuracy 1
step 13200, training accuracy 1
step 13300, training accuracy 1
step 13400, training accuracy 1
step 13500, training accuracy 1
step 13600, training accuracy 1
step 13700, training accuracy 1
step 13800, training accuracy 1
step 13900, training accuracy 1
step 14000, training accuracy 1
step 14100, training accuracy 1
step 14200, training accuracy 0.98
step 14300, training accuracy 0.98
step 14400, training accuracy 1
step 14500, training accuracy 1
step 14600, training accuracy 1
step 14700, training accuracy 1
step 14800, training accuracy 1
step 14900, training accuracy 1
step 15000, training accuracy 1
step 15100, training accuracy 1
step 15200, training accuracy 1
step 15300, training accuracy 1
step 15400, training accuracy 1
step 15500, training accuracy 0.98
step 15600, training accuracy 1
step 15700, training accuracy 1
step 15800, training accuracy 1
step 15900, training accuracy 1
step 16000, training accuracy 1
step 16100, training accuracy 1
step 16200, training accuracy 1
step 16300, training accuracy 1
step 16400, training accuracy 1
step 16500, training accuracy 0.98
step 16600, training accuracy 1
step 16700, training accuracy 1
step 16800, training accuracy 1
step 16900, training accuracy 1
step 17000, training accuracy 1
step 17100, training accuracy 1
step 17200, training accuracy 1
step 17300, training accuracy 1
step 17400, training accuracy 1
step 17500, training accuracy 1
step 17600, training accuracy 1
step 17700, training accuracy 1
step 17800, training accuracy 1
step 17900, training accuracy 1
step 18000, training accuracy 1
step 18100, training accuracy 1
step 18200, training accuracy 1
step 18300, training accuracy 1
step 18400, training accuracy 1
step 18500, training accuracy 1
step 18600, training accuracy 1
step 18700, training accuracy 1
step 18800, training accuracy 1
step 18900, training accuracy 1
step 19000, training accuracy 1
step 19100, training accuracy 1
step 19200, training accuracy 1
step 19300, training accuracy 1
step 19400, training accuracy 1
step 19500, training accuracy 1
step 19600, training accuracy 1
step 19700, training accuracy 1
step 19800, training accuracy 1
step 19900, training accuracy 1
test accuracy 0.9922


# Accuracy on test set is 99.22%
So now after evaluating the model on our test set we got accuracy of 99.22% which is fair enough to be deployed and used in the global environment.
