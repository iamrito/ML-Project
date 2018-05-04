EE769: INTRODUCTION TO MACHINE LEARNING: COURSE PROJECT SUBMISSION   
(Amrit Kumar Muduli, Mahera Mulla, P T Cherishma)

The automated recognition of handwritten alphabets and digits is a largely studied problem which connects the ﬁelds of Computer Vision and Machine Learning and has many applications in real life. The aim of this project is to implement a handwritten digit and alphabet recognition system using convolutional neural networks (CNNs). The CNN proposed here is experimented on the well-known MNIST data set for digit recognition and UCI Machine Learning Repository for alphabets.

This submission contains the following files. 

1. Alphabets_Digits_Recognizer.ipynb
This is the python script that takes the input data from UCI Machine Learning repository and applies CNN to it and gives the output model as my_model_az.h5. To excecute the code please download the dataset from UCI Machine Learning repository as 'A_Z Handwritten Data'. The code also has illustrative graphs and figures required to visualise the trend in accuracy(train and validation), some misclassified examples etc. 

2. Digit_Recognizer.ipynb
This python script takes the input data as provided in the Kaggle competition 'Digit Recognizer' and trains a CNN and gives the output model as my_model.h5. This code was also submitted on Kaggle for Digit Recognizer competition.

3. Input_Camera_Alphas_Digits.ipynb
An input image which has both alphabets and numerals is taken and the model is tested on this data set and the results of prediction are also included.  

4. Input_Camera_Digits.ipynb
An image is taken using camera and is processed and is used as test data to test the saved model 'my_model.h5'.

5. amrit_hw.jpg, cherry_hw.jpg, swas_hw.jpg
These are the input images that were taken using a camera for testing our models. 

