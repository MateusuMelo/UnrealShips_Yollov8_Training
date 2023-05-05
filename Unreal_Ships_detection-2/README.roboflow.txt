
Unreal_Ships_detection - v2 2023-05-03 12:19pm
==============================

This dataset was exported via roboflow.com on May 3, 2023 at 4:32 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 19362 images.
Ships-Types are annotated in YOLOv8 format.

The following pre-processing was applied to each image:

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Randomly crop between 0 and 53 percent of the image
* Random shear of between -14° to +14° horizontally and -21° to +21° vertically
* Random exposure adjustment of between -43 and +43 percent
* Random Gaussian blur of between 0 and 6.75 pixels
* Salt and pepper noise was applied to 13 percent of pixels


