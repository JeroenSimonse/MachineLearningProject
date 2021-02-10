# General info
This project was part of our Machine Learning course and consisted of the following two tasks:
1. Image classification
	* Using and testing MLP and CNN models
2. Using the best performing classifier from task 1, to identify a series of five letters in one image

The models from task 1 were trained and tested on the MNIST dataset. For the second task, our professor a custom dataset. 

---

## Technologies
The project is coded in:
Python V3.7

Using the following libraries:
* numpy
* pandas
* tensorflow
* matplotlib
* math
* sklearn
* keras
* collections
* seaborn
* os
* imutils

Tools that were used:
* Google colab 
* Anaconda

---

## Usage
Make sure the path to the test and training data is adjusted to the right path, otherwise this code doesn't work. 

---

## Note
The results of our first task were very good and scored an accuracy of ~97%. Although the model of task 1 was performing very good, the results of task 2 were disappointing.
This was largely due to the approach we had, which was a *fixed* sliding window that selected and classified 1/5th of the image per prediction. However, due to the letters
being in random places within the image, this did not work. Perhaps edge detecting would have worked better. 
