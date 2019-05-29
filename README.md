# AutoEncoders-for-Outlier-Detection
AutoEncoders for visual data

I have created a custom AutoEncoder model to reconstruct images and detect outliers.

We are able to check the outliers based on the mean squared error between the input image and the reconstructed image.
Since the reconstruction is not very accurate for an image with the input size of 224x224, we plot the errors to find a threshold to seperate the required class from the outliers.
