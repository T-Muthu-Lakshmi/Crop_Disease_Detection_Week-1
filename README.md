Crop_Disease_Detection
Week_1: Data Pre-processing

1) We have a dataset 5 different crops. Each crop folder is further divided into disease classes.

2) Sample Visualization: A random image from each class is displayed using matplotlib. We are doing this to check if the image matches the label.

3) Then we prepare the image: a) Resizing (224x224),
                              b) Normalizing(0-255 -> 0-1)
                              c) Augmentation by rotating, flipping etc. to increase robustness.

4) In this week we have ensured that our data is organized, divided by class labels, visualized and is in proper format for training.
