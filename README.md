# Ion-Recognition-Machine-Learning
The purpose is to generate a set of data for training a Neural Network to recognise ions on CCD image exposures during an ion trapping experiment. Initally, I am trying to generate somewhat realistic ion images and noise to see if it is possible for the network to discern an ion on the camera image. Ideally, this can then be used to automate the trapping procedure and help to detect dim and obscured ion images amid noisy images during trapping runs.

The data is generated in the script but is included in the "Sim_Image_Data.zip" file. A Convolutional Neural Network is then built, trained and benchmarked, to be capable of taking input images from camera exposures during experimental ion trapping runs and classifying for the presence of an ion on the noisy image.

This is done here using data which may not be entirely realistic, however the generalised model could be trained on real image data in the same manner.
