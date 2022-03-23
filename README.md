# Building An Image Calssifier
Trying multiple models for image classifications:
* Model 1: A logistic classifier built directly on the pixesl of the images which behaved in a very bad way as expected.
* Model 2 (Using transfer learning): Using the feature extrated by ImageNet pre trained network, a logistic classifier was trained over the extracted features to classify the images.
* Model 3: A classifier model built using enemble of nearest_neighbor models to classify the images.