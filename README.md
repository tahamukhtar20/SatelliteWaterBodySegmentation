# Segmentation of satellite images of water bodies

The dataset used in this work includes 2841 RGB images and 2841 black-and-white masks and can be found on the Kaggle website.

https://www.kaggle.com/datasets/franciscoescobar/satellite-images-of-water-bodies

This project is built on top of https://github.com/tstran155/Segmentation-of-satellite-images-of-water-bodies/blob/main/Notebook1_satellite_images_segmentation_final.ipynb but the different models have been tested on top of the originally provided ones. The model which you can find in this notebook is UNet, which is well known to work well against satellite images, with a custom loss function utilizing both dice and bce loss.

The old model gave a 62% val_accuracy, whereas this one is capable of providing ~ 75% val_accuracy which is considered a good accuracy when it comes to Satellite Imagery.
