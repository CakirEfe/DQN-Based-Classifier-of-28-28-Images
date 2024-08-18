# DQN-Based-Classifier-of-28-28-Images
Identifies electric motor faults using vibration data converted to 28*28 images

Initially, a new custom dataset is created from the uOttawa Electric Motor vibration dataset using the RawDataTo28_28 script. It converts the first row of each file (accelerometer 1) in the uOttawa dataset to 28x28 images ready to be uploaded

The new custom dataset is then uploaded to the DQN in the other script to be trained with.

I will change the image generator to take in the other 3 rows as well in the future, it was just more convenient for now this way
