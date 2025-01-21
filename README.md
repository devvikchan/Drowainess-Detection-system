# Drowsiness-Detection-system\
In this project, we will use transfer learning to build the model. Transfer Learning is a machine learning method where we use a pre-trained model for a new model with the related problem statement.
The methodology of this project is the first video is captured using a webcam and from the video first face is detected using the Harcascade algorithm and then the eyes are detected. Then we use our deep learning model which is built using transfer learning to know the status of the eye. If it is an open eye then it will say Active and if it is a closed eye then it will check for a few seconds and then it will say the driver is drowsy and will beep an alarm.

We will use Python, OpenCV, TensorFlow, and Keras to build a system that can detect the closed eyes of drivers and alert them if ever they fall asleep while driving. If the driver’s eyes are closed, this system will immediately inform the driver. OpenCV that we are going to use now will monitor and collect the driver’s images via a webcam that was attached and feed them into the deep learning model and then the model will classify the driver’s eyes as ‘open’ or ‘closed.’

