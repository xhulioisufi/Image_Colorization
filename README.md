# Image_Colorization
This study addresses the challenge of generating a realistic color version of a given grayscale image. 
The system that achieves this output is implemented as an Convolution Neural Network. A CNN that has been trained to predict an image's colors based on its features and patterns can be used to accomplish our task. 
Our model gets as input the lightness channel ('L') from an image and predicts the corresponding 'A' and 'B' color channels of the image in the CIE Lab colorspace. 
Our model will be used as an auto-encoder , where the channel 'A' & 'B' that we will predict, will be extracted from our input. 
**In this repository you will find the best architecture that I created plus the saved model, so you can test on your own data.**
