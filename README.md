The dataset file which is train_data.zip, contrains image data which has 4 type of gestures and a background image. Each image class contains around 500 images.
The file handgesture.py containes the training code which extracts the data from the zipped file and trains the model. It contains two convolutional layers with maxpooling and reluc activation. And at last the linear activation is used.
The trained_model.pth is the final model as a result of the training. We can use the model directly also.
