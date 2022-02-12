# Convolutional-Neural-networks-in-TensorFlow
Convolutional neural networks implementation using tensorflow. This course is available on coursera, it covers image classification using convolutional neural networks using keras sequential API. In the first week, image classification is coverd without using data augmentation. The model peformance is not very good, for instance, its around 70%.

However, in the week 2, the model performance has been improved using data augmentation options such as rotations, translations, fliping, zooming, shear, and so on. In first two weeks custom designed convolutional neural network has been used, for example, 32 kernels in the first conv layer and 64 kernels in the second and final conv layer.

In the third week, no custom designed model has been experimented. InceptionV3 has been used, and it is trained on final layers while keeping other layers untrainable. It has been trained on horses and humans dataset. Data augmentation has also been applied. The model achieved 99.6% validation accuracy on the dataset. It shows that transfer learning and data augmentations are very powerful techniques for training a deep learning model. Which improves a deep learning model's performance substantially.

In the Final week, sign language recognition dataset has been used. In this week, the model has been trained on multi-classes, in this case 26 classes. Again in this week, a custom CNN model has been designed using Keras sequentail API.

#Note
Please use contents in this repository, if you are stuck in your programming assignments and quizes. If you don't understand anything or if you tried but you are still don't undertand certain details in this repository. don't worry! Please email me engrfaizan.ai@gmail.com
