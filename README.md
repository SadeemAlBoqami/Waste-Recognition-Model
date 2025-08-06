# Waste Recognition Model
An artificial intelligence model using Teachable Machine to recognize and classify waste images (paper-wood-plastic-glass-organic).

First, I used Teachable Machine to train the model to categorize waste into glass/plastic/paper/wood/organic material, using a huge image set I found on Kaggle. The average number of images on which each class was trained is about 800-1000 images.

Dataset from kaggle: https://www.kaggle.com/datasets/angelikasita/waste-images

Then I trained the model and exported it to the TensorFlow - Keras file, from the site the model file was created and the accompanying Python code "we copy" to be able to run it
To run the code I used Google Collab, which is an excellent editor for running code on Google Cloud resources.

I created a new file and pasted the TensorFlow code into it, uploaded the Keras file, the label and the images where I will test the model.

Now to test the code, we modify the code, specifically the line `image = image.open(”<IMAGE_PATH>“).convert(‘RGB’)` type test image extension, run the code, and we see the output immediately.



