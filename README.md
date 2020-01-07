# Image Classification: Dogs-vs-Cats

#### Using Transfer Learning from Keras InceptionNet V3

Classifying images of dogs and cats from Kaggle using Keras application InceptionNetV3 Neural Network model pre-trained on ImageNet dataset with a fully connected hidden layer of 512 neurons included on top, ending with a layer of Softmax activation as the final probability estimation layer. This model was trained to minimize categorical cross-entropy using a Stochastic Gradient Descent optimizer after initial image pre-processing and augmentation using ImageDataGenarator.