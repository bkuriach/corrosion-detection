
Synthetic Corrosion Dataset - v3 2022-08-16 10:23am
==============================

This dataset was exported via roboflow.com on August 16, 2022 at 3:24 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 292 images.
Corrosion are annotated in folder format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 540x540 (Stretch)

The following augmentation was applied to create 5 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Random rotation of between -15 and +15 degrees
* Random brigthness adjustment of between -20 and +20 percent


