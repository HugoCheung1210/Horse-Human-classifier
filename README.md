# Horse-Human-classifier


Run the code blocks below to download the datasets horse-or-human.zip and validation-horse-or-human.zip respectively.

Then unzip both archives.

Define the directories containing your images.

Setup the data generators. It will mostly be the same as last time but notice the additional code to also prepare the validation data. It will need to be instantiated separately and also scaled to have [0,1] range of pixel values.

Train the model for 15 epochs. Here, you will pass parameters for validation_data and validation_steps. With these, you will notice additional outputs in the print statements: val_loss and val_accuracy. Notice that as you train with more epochs, your training accuracy might go up but your validation accuracy goes down. This can be a sign of overfitting and you need to prevent your model from reaching this point.

Now take a look at actually running a prediction using the model. This code will allow you to choose 1 or more files from your file system, upload them, and run them through the model, giving an indication of whether the object is a horse or a human.

Important Note: Due to some compatibility issues, the following code block will result in an error after you select the images(s) to upload if you are running this notebook as a Colab on the Safari browser. For all other browsers, continue with the next code block and ignore the next one after it.

For Safari users: please comment out or skip the code block below, uncomment the next code block and run it.
