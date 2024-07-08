# Digitising-a-string-of-numbers
<br />
this is a model for digitising the strings of numerical numbers using opencv and tensorflow(neural networks)
<br /><br />
<h2>Ok so first let's start with how it works?</h2><br /><br />
The model(mnist_model.h5) is made and trained by me on the mnist dataset on over 60000 images to identify the images for digits from 0 to 9.<br />
the result is quite considerable getting an error of 0.5% - 0.7% on trained dataset and 2.4%- 3.0% on testing dataset<br />
 
<br /> <br /> 
After training the model i worked on image segmentaion using open cv to convert a image of a string of numbers into different images of <br /> each digit ,
so that it can be fed into the model to generate the digitsed string.<br />
<br />
Although to be honest the model is quite fine but the image segmentation part is not that accurate due to unavailabilty 
of any online dataset. i tried 
it on custom images captured on my phone, but sometimes there seems to be some problem with noises and the accuracy of countours. <br /><br /> 
This consists of two files apart from readme mnist file contains the trained model, and main file is jupyter file that contains all the code, it also contains all many cells for debugging that will definitely help you all<br /><br />

I want to give credit to the coursera for the courses on machine learning that helped me in doing this project<br />

have a good day <br />
improvements will be there!
