# Fabric-Defect-Recognition-using-Deep-Learning
This is my Bachelor's Degree Thesis

Problem Definition
The problem addressed by the application developed in this thesis is the simulation of an automated process for detecting and classifying defects in a piece of material by capturing images during the inspection process and visualizing the defects on the original image. The images have a resolution of 1024x1024, simulating the size of an image that can be processed by an in-line camera, commonly found in textile manufacturing production lines.

Objectives of the Study
This research aims to explore detection and classification algorithms for processing fabric manufacturing defects. The ultimate goal of the application is to successfully identify and classify defects into one of the following seven categories: "pinhole," "small hole," "stitching defect," "loose thread," "hole," "spot," and "scratch," and visualize them on the original image.

The defects originate from a database created by Simon Thomine [8], which follows the same nomenclature as the MVTec Anomaly Detection Dataset [9]. To closely mimic an image captured by a factory camera, collages of 16 images were created to achieve a 1024x1024 resolution.

For image recognition and processing, the following software tools were used:

TensorFlow, Ultralytics, Keras
Additional libraries: OpenCV, NumPy, Pillow, Matplotlib, Shutil
For defect detection, the YOLOv8 architecture was employed, while for classification of the detected defects, the VGG19 architecture was used.

Finally, the defects were represented in collages with colored bounding boxes and labels, indicating the type of defect identified in each image section.
