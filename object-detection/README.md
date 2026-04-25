# Raccoon Object Detection with R-CNN

This project implements an R-CNN style object detection pipeline for raccoon localization using a public image dataset with VOC/XML annotations.

### Methods
- VOC/XML annotation parsing
- Selective Search for region proposals
- IoU-based positive/negative sample assignment
- VGG16 feature extractor
- Classification head and bounding-box regression head
- Non-Maximum Suppression (NMS)
- Prediction visualization

### Tools
Python, PyTorch, TorchVision, OpenCV, NumPy, Matplotlib

