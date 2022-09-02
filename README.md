# PREDICTING-HANDWRITTEN-DIGITS

# INTRODUCTION

The topic of digit recognition is significant and crucial. Because the manually written digits do not have the same size, thickness, position, or direction, various difficulties must be considered in this approach. Identify the problem with handwritten digit recognition. Handwritten Digit Recognition is a computer's ability to interpret manually written digits from a variety of sources, such as messages, bank cheques, papers, pictures, and so on, and in a variety of situations, such as web-based handwriting recognition on PC tablets, identifying vehicle number plates, handling bank cheques, and digits entered in any form.
Pattern Recognition using Machine Learning gives several approaches for reducing human effort in detecting manually typed numbers.
With the help of pattern classifier using supervised learning, we can build our model architecture and train the model to determine the digit pattern easily.
The Convolutional neural network from Machine Learning can be used to recognise handwritten digits. The core structure of my project development is based on the MNIST database and CNN compilation.

![image](https://user-images.githubusercontent.com/25850136/188219533-432e676c-da71-467f-9dc0-b919d0441942.png)
### Fig. Proposed Approach

Enviorment:
- Pyhton 3.6+
- Jupyter Notebook/Google Colab
- Windows 10/11
- Necessary Python Libraries

How to Run ?

1. Keep .h5 file in the same location where FINAL_PR_GUI.ipynb file has been stored.
2. To run the UI, you need to execute FINAL_PR_GUI.ipynb file

![image](https://user-images.githubusercontent.com/25850136/188219862-58d97796-701b-48b1-b71d-48404f38dd87.png)
DATASET: http://yann.lecun.com/exdb/mnist/

# OUTPUT

![image](https://user-images.githubusercontent.com/25850136/188220914-8cee1fc6-4570-47ef-9a43-4d33d2e25a29.png)
### INITITAL INTERFACE

![image](https://user-images.githubusercontent.com/25850136/188220998-0aac0f97-61e7-4a15-8306-e38c363c9f91.png)
### DIGIT PREDICTION

![image](https://user-images.githubusercontent.com/25850136/188221246-de7a7379-8032-4b48-b433-f63b1cee9272.png)
### PREDICTION

# RESULT
The principle behind nearest neighbor methods is to find a predefined number of training samples closest in distance to the new point and predict the label from these.
It has one of the simplest learning strategies: given a new, unknown observation, look up in your reference database which ones have the closest features and assign the predominant class.
The distance can, in general, be any metric measure: standard Euclidean distance is the most common choice.
In the digit prediction we have used k = 9 for kNN algorithm on which our model has been trained. Hence, I have achieved 98.36 % accuracy with very minimal loss 0.0250.
With the help of user interface, we can draw digit with the help of mouse interaction and predict the digit with good results which I have shown in results section![image](https://user-images.githubusercontent.com/25850136/188221320-be95b9c7-5153-40ec-a869-6f82f29a7aa3.png)

