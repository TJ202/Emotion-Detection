# Emotion Detection Using Facial Recognition with CNNs

Most deep learning applications are only quantified with respect to its accuracy in making predictions or classifications. In an IoT application, this is not the only aspect of concern. Through this project we wish to quantise metrics that are usually ignored that are essential in an IoT application. These metrics can serve as a benchmark when developing deep learning models that are to be deployed in IoT applications.

## How to run?

- Clone the repository and Obtained the pre-trained models CNN and RESNET50 from following drive link in the same directory.
- Create 2 folders named 'captured-images' and 'greyscaled-images' in the same directory.
- Run ```webcam-capture.py``` to enable the webcam and press 's' to save the pictures in folder named 'captured-images'.
- Once images are saved, press 'q' to quit the application.
- Go to ```load.py``` and click on ```Run All``` to run all the cells.
- The models will make predictions for images given to the ```CNN_pred_and_plot``` and the ```resnet_pred_and_plot``` functions and show them with the predicted class.
