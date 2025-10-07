This repository contains the implementation for my MSc dissertation “Robust Vehicle Detection for Safe Autonomous Vehicle Navigation in Foggy Weather Condition.”
The project investigates how data-centric augmentation can improve camera-based object detection for autonomous vehicles under foggy weather.

Using YOLOv8, the study explores two main robustness strategies:

Physics-based fog modelling – simulating realistic fog in training images

Neural Style Transfer (NST) – adapting clear images to foggy domains

Models are trained on the BDD100K dataset (clear weather) and evaluated on the DAWN dataset (real fog) to test cross-domain generalisation.
Results show that lightweight YOLO variants (like YOLOv8-nano) can achieve strong detection performance in fog with minimal computational cost.


![Training Strategy](https://raw.githubusercontent.com/alishaheb/object_detection_yolo/865543eae886fe6eb3bb23a920cb6cf2e09d3d32/training_strategy.png)
