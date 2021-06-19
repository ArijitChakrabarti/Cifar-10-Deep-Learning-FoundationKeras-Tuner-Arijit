# Object Recognition from  CIFAR 10 images
<center><img src="https://github.com/ArijitChakrabarti/Cifar-10-Deep-Learning-FoundationKeras-Tuner-Arijit/blob/main/CIFAR-10-intro.jpg?raw=true" /></center>

<h2><center>'One picture is worth a thousand words'</center></h2>
<div style="text-align: center"> -Albert Einstein</div><br>

***

Images somehow just always make sense - as accurately captured by Albert Einstein.  From my initiation into regimented learning of data science I have worked multiple times on the MNIST dataset.  For this project I wanted to take up something a bit more challenging and also build onto the overall knowledge base of image classification.  Further, I wanted to automate the process of identifying the hyper parameters that would build accuracy for an image classification model.
<br><br>
Armed with these simple points I wanted to find a data-base, which would a step up over  MNIST dataset in terms of difficulty - maybe allowing me to work with color - but not so demanding that I lose focus on the learning outcome of this project.
<br><br>
After searching high and low I found the CIFAR 10 data-set.  It was beautifully arranged set of .png files, and also existed as a dataset in Keras. However, I wanted to start working directly from the pictures itself (converting the image to an array) and not use the existing data-set.  I was also secure in the knowledge that since the dataset also existed in array form I could always cross-check my data and compare it against the data-set to check for possible errors.  My project contains many such checks to ensure that the data was properly convered to the array.
*** 
<br><br>
Hence the project itself can actually be summarized in the following manner:
<br><br>
- Downloaded the CIFAR - 10 .png images from Kaggle
<br><br>
- Converted the images to an array
<br><br>
- Processed the array to make it usable
<br><br>
- Built multiple models on the data with a close check on accuracy
<br>
    - A simple Artificial Neural Network model
<br>
    - A CNN model - built from secondary sources
<br>
    - Using Keras Tuner to enhance the accuracy on the models leveraging
        | Hyperband serach | Random search | Bayesian Optimization | 
<br><br>
- Comparision of the outcomes of the different models 

You can download the CIFAR 10 dataset from kaggle -> https://www.kaggle.com/c/cifar-10
