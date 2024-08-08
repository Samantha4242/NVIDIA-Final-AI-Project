# NVIDIA Final AI Project 

This project is an AI which detects and identifies different types of tabletop role play game dice such as a D20. This ai utilizes an array of data which is used to train the ai with the different shapes and names of the dice. 

[View a image of the final result here!] https://github.com/user-attachments/assets/4fc28486-beb2-44df-ba86-e16489147322


# The Algorithm

This project uses the NumPy library, also known as Numerical Python, which supports large, multi-dimensional arrays which also excels in performing optimized mathematical operations on large arrays. This is very helpful for this project as it allows a person to test whether any array element along a given axis evaluates to True. Numpy is fundamental to this project as it forms the foundation of Machine Learning as it helps hold all the training, test, and validation data. This also allows very efficient data handling, manipulation, and analysis of the data saved which is vital to machine learning.

This project also utilizes the Pytorch Library which is a machine learning library. This is an open source machine learning library used for developing and training neural network based deep learning models. This library is known to be extremely useful for research and small-scale projects and is mainly used for applications using GPUs and CPUs.

This project also uses the Resnet18 Network which is a convolutional neural network, which is deep learning that learns directly from data, that is 18 layers deep and is pre-trained on ImageNet dataset, which consists of three parts: training data, validation data, and image labels and is useful for finding patterns in images to recognize objects, classes, and categories. It tackles the vanishing gradient problem using skip connections and shortcuts, and is more specifically used for computer vision applications like object detection and image segmentation. 

This project was built with a dataset from kaggle. This data set is called "Dice: d4, d6, d8, d10, d12, d20 Images" and was created by Mario Lurig. This data set 16,000 custom images of all 6 diffrent dice shapes and comes with images for the test and validation.

[View the kaggle dataset here!] https://www.kaggle.com/datasets/ucffool/dice-d4-d6-d8-d10-d12-d20-images?resource=download


# Running this project

1. Download the code and add to an app such as visual studio code
2. Go into the "Final Project" Directory
3. Run the "python3 imagenet.py" command
4. Input a image url when prompted
5. Input the name it will be saved under when prompted
6. Check the final product which will be inside the "Final Project" directory and will be under "(The name you inputed)_Output.jpg"

# Libraries needed to use this code:
 1. NumPy
 2. PyTorch


[View a video demo here!] https://drive.google.com/file/d/1ZrAYNnGF_0a7_wzk4EMNN_dxzI5j8wpc/view?usp=sharing
