# Dog_classification
In this project we have 2 main objectives:
1) Identifying which pet images are of dogs and which pet images aren't of dogs
2) Classifying the breeds of dogs, for the images that are of dogs

# Tasks:
Using Python skills, we will determine which image classification algorithm works the "best" on classifying images as "dogs" or "not dogs".
Determine how well the "best" classification algorithm works on correctly identifying a dog's breed. If we are confused by the term image classifier look at it simply as a tool that has an input and an output. The Input is an image. The output determines what the image depicts. (for example, a dog). Be mindful of the fact that image classifiers do not always categorize the images correctly.
calculate time how long each algorithm takes to solve the classification problem. With computational tasks, there is often a trade-off between accuracy and runtime. The more accurate an algorithm, the higher the likelihood that it will take more time to run and use more computational resources to run.

For this image classification task, we will be using an image classification application using a deep learning model called a convolutional neural network (often abbreviated as CNN). CNNs work particularly well for detecting features in images like colors, textures, and edges; then using these features to identify objects in the images. we'll use a CNN that has already learned the features from a giant dataset of 1.2 million images called ImageNet. There are different types of CNNs that have different structures (architectures) that work better or worse depending on your criteria. With this project, we'll explore the three different architectures (AlexNet, VGG, and ResNet) and determine which is best for your application.

# Image Classification Results
# Image Counts
| Metric           | Count |
| ---------------- | ----- |
| Total Images     | 40    |
| Dog Images       | 30    |
| Not-a-Dog Images | 10    |

# Model Accuracy Results
| CNN Model Architecture | % Not-a-Dog Correct | % Dogs Correct | % Breeds Correct | % Match Labels |
| ---------------------- | ------------------- | -------------- | ---------------- | -------------- |
| ResNet                 | 90.0%               | 100.0%         | 90.0%            | 82.5%          |
| AlexNet                | 100.0%              | 100.0%         | 80.0%            | 75.0%          |
| VGG                    | 100.0%              | 100.0%         | 93.3%            | 87.5%          |

The "best" model architecture is VGG. It outperformed both of the other architectures when considering both objectives 1 and 2. we will notice that ResNet did classify dog breeds better than AlexNet, but only VGG and AlexNet were able to classify "dogs" and "not-a-dog" at 100% accuracy. The model VGG was the one that was able to classify "dogs" and "not-a-dog" with 100% accuracy and had the best performance regarding breed classification with 93.3% accuracy.
