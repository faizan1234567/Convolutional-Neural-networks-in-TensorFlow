

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) ![Python](https://img.shields.io/badge/python-3.6-blue.svg)
![Repo Size](https://img.shields.io/github/repo-size/faizan1234567/Convolutional-Neural-networks-in-TensorFlow) 
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


## Convolutional Neural Networks Implementation
This repository contains solved assignments and quizzes for [Convolutional Neural Networks course](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow).
Furthermore, it contains examples of CNN Implementation in TensorFlow.


## Course Information
[In this course](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow), you will explore how to work with real-world
images in different shapes and sizes, visualize the
journey of an image through convolutions to
understand how a computer “sees” information,
plot loss and accuracy, and explore strategies
to prevent overfitting, including augmentation
and dropout. Finally, [this course](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow) will
introduce you to transfer
learning and how learned features can be
extracted from models. 

## Skills You Will Gain
After practicing examples in this course, you will learn the following skills.

- Augmentation
- Dropouts
- Machine Learning
- Inductive Transfer
- TensorFlow
- Data preprocessing


## Credits
This repository my work for this course. This has
been created to help learners when they are stuck in programming assignments. The code base, quiz questions, and  diagrams are taken from the [Convolutional Neural Networks with TensorFlow](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow).




## Installation
```bash
!git clone https://github.com/faizan1234567/Convolutional-Neural-networks-in-TensorFlow
cd Convolutional-Neural-networks-in-TensorFlow
``` 
create virtual environment
```bash
python -m venv --system-site-packages .\CNN_with_tf
```
Activate the virtual environment
 ```bash
.\CNN_with_tf\Scripts\Activate
 ```
 Install packages within a virtual environment without affecting the host system setup. Start by upgrading pip:
 ```bash
 pip install --upgrade pip
 pip list  # show packages installed within the virtual environment
 ```
 And to exit the virtual environment later:
```bash
deactivate  # don't exit until you're done using TensorFlow
 ```
 Now install TensorFlow
 ```bash
 pip install --upgrade tensorflow
  ```
To check everything works perfectly, run the following command
```bash
python -c "import tensorflow as tf;print(tf.reduce_sum(tf.random.normal([1000, 1000])))"
 ```
You are all set to use tensorflow now. Please follow the notebooks to import or install modules.





## Programming Assignments and Quizzes 
- Week 1 
  
  - [Cats Vs Dogs Classification](https://github.com/faizan1234567/Convolutional-Neural-networks-in-TensorFlow/blob/main/week1/Exercise_1_Cats_vs_Dogs_Question-FINAL.ipynb)
  - [Quiz](https://github.com/faizan1234567/Convolutional-Neural-networks-in-TensorFlow/tree/main/week1/quiz)

- Week 2
  
  - [Cats Vs Dogs with augmentation](https://github.com/faizan1234567/Convolutional-Neural-networks-in-TensorFlow/blob/main/week2/Exercise_2_Cats_vs_Dogs_using_augmentation_Question-FINAL.ipynb)
  - [Quiz](https://github.com/faizan1234567/Convolutional-Neural-networks-in-TensorFlow/tree/main/week2/quiz)

- Week 3

  - [Horses Vs Humans classification using Transfer Learning](https://github.com/faizan1234567/Convolutional-Neural-networks-in-TensorFlow/blob/main/week3/Exercise_3_Horses_vs_humans_using_Transfer_Learning_Question-FINAL.ipynb)
  - [Quiz](https://github.com/faizan1234567/Convolutional-Neural-networks-in-TensorFlow/tree/main/week3/quiz)

- Week 4

  - [Multi-Class Classification](https://github.com/faizan1234567/Convolutional-Neural-networks-in-TensorFlow/blob/main/week4/Exercise_4_Multi_class_classifier_Question-FINAL.ipynb)
  - [Quiz](https://github.com/faizan1234567/Convolutional-Neural-networks-in-TensorFlow/tree/main/week4/quiz)
  
## Disclaimer
Programming assignments solutions has been provided for reference.
Please don't copy and paste, as Programming assignments are fairly simple if you have followed 
the lectures. This solution is for hints and to keep you motivated to learn. If you are stuck in your 
programming assignments, please take it as help.
