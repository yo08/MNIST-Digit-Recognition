# MNIST-Digit-Recognition
Building a DL model for scratch for handwrittten digit recognition using MNIST dataset

______________________________________
*Files description*
______________________________________

my-final-model-training-and-saving.ipynb
      - Building the model
      - training it and obtaining the following metrics:  accuracy= 99.440  |   loss= 0.0216
      - saving the trained model as a .h5 file
 
my-final-model-loading-evaluating-converting-to-c.ipynb
      - importing teb previously saved model and evaluating its performance on the test data
      - making a prediction of a manually loaded handwritten digit for verification purposes
      - converting the keras model into a tflite model, to finally convert it to a C header file (the model was next embedded on an STM32 microcontroller)
