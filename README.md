# SpheronisationCategorisation
A 640x640 mobilenet neural network trained to detect and categorise pellets undergoing spheronisation.

Mobilenet downloaded from the TensorFlow model zoo and trained using the tensorflow object detection API.

Detects the position of the pellets and attempts to categorise them as one of the following:

* Sphere - final output of the spheroniser
* Dumbbell - pellet with both ends rounded and where both ends are wider than the centre
* Cigar - Similar to dumbbell but without a waist or where only one end is rounded
* Rod - Unworked section of paste
