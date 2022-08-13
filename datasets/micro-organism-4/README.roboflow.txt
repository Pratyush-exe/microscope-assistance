
micro-organism - v4 2022-08-13 4:07pm
==============================

This dataset was exported via roboflow.com on August 13, 2022 at 10:37 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 859 images.
Micro-organism are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Resize to 416x416 (Stretch)
* Grayscale (CRT phosphor)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Random rotation of between -20 and +20 degrees
* Random shear of between -20° to +20° horizontally and -20° to +20° vertically


