# Facial Expression Recognistion using Deep Learning

I used the ResNet9 architecture and PyTorch as my choice of framework to train a model to recognise facial expressions 
and classify them as one of 7 classes: (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).
<br><br>

The [dataset](https://www.kaggle.com/datasets/msambare/fer2013) contains 28,709 training examples and 3,589 testing examples of 48x48 grayscale images. 
However, the distribution of images among the different classes is far from even as shown in the figure below: <br><br>
![image](https://user-images.githubusercontent.com/67051265/164959903-9fdb263b-c9d7-40e7-81eb-465251eb897f.png)

<br>

After training the model there is a snippet of code at the end which you can use to recognise expressions in your own images as demonstrated (please use square crops).
<br>
Open the images as PIL images, apply the defined transform and use the predict_img() function to generate your own predictions.
