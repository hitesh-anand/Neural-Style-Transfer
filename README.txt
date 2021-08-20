AIM:- 

Created a neural style transfer model. It takes as input a content image and a style image to generated a new image which has content of the first image styled according to the second image.

ACKNOWLEDGEMENTS:-

The Code was initially completed in the 4th course of Deep Learning Specialization by DeepLearning.Ai on Coursera. This was provided as a programming assignment in the last week. The basic structure+algorithm+functions are same as provided there. I have just changed a few things to visualize the generated images in a better way and to use the images of our choice from our device.


MODEL:-

The model uses pretrained weights of 'vgg19_weights_tf_dim_ordering_tf_kernels_notop.h5' model (see the second cell).


SUGGESTIONS TO RUN THE PROGRAM ON YOUR DEVICE USING YOUR IMAGES:-

Download the main notebook and the pretrained model from this repo to your system.

Just run all the cells from the start and change the location of image as and when required. For example, while loading the third image in the third cell, use appropriate location of the image you want to use as the content image. In my case, the image was in the same folder as my notebook and hence, I just used the name of the image and not any folder before it. Similarly display the style image of your choice.

Run all the cells that define functions. The comments were earlier also provided and will be updated soon where ever I feel it is required for the user, along with the mathematical concepts behind this model.

So keep running all the cells. The only error you will see is when you have accidentally put a wrong location of the image you want to test. So be cautious here.

In the training cell(starting with the line 'epochs=2501'), the second line asks to save the image in a folder named 'output'. So create this folder beforehand at the desired location where you want to store the intermediate images. According to current parameters, After each 5 turns, the resulting image will be saved on your device. To change this, you can change the second "if" condition in the training cell before running it. (Change the value from 5 to something else.)

ADDITIONAL TRAINING SUGGESTIONS:-

This model has been trained on a CPU and it took me around 2 hours to complete its training.

For faster training, just reduce the number of epochs before training. Currently it is set to 2501. You may want to stop the process earlier depending on your purpose and hence I have changed the frequency of showing intermediate images to 5(originally it was 250.)
So you can easily visualize where do you want to stop.




So, enjoy the beauty of Neural Style Transfer and feel free to contact me in case of any issues.

