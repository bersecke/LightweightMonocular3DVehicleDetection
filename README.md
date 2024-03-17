# Lightweight Monocular 3D Vehicle Detection

Master's project exploring the development of a lightweight monocular model for the detection of cars with 3D bounding boxes.

## Abstract 

This paper explores the 3D vehicle detection problem based exclusively on monocular images, placing emphasis on creating the simplest possible yet functional models for the task. The main concept behind the CenterNet system is taken as a foundation for this purpose, involving the detection of vehicle centers and the regression of other parameters that provide further location and pose information. Several lightweight architectures with U-Net-like feature extractors are tested to implement this concept in a simplified manner, which use only a fraction of the parameters that constitute the original CenterNet model. A case with calibrated cameras is first addressed, where several model variants capable of predicting the location and orientation of 3D bounding boxes enclosing vehicles are designed for the KITTI dataset. The feasibility of estimating this same information when dealing with uncalibrated cameras is later explored through the simplification of the 3D detection problem into 2D. Images from the Ko-PER traffic monitoring dataset are first transformed into their bird’s-eye view (BEV) versions using homographies, and vehicles are then detected as rotated bounding boxes in a 2D plane.
