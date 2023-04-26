# R-cnn-Object-Detection
This repository contains the implementation of the R-CNN (Region-based Convolutional Neural Networks) object detection algorithm using PyTorch.

### Introduction
R-CNN is a widely used object detection algorithm that was proposed by Ross Girshick et al. in their paper, "Rich feature hierarchies for accurate object detection and semantic segmentation." The R-CNN approach consists of three steps:

Region Proposal: generate a set of region proposals using a selective search algorithm.
Feature Extraction: extract a fixed-length feature vector from each region proposal using a pre-trained CNN (Convolutional Neural Network).
Object Classification: classify the region proposals into different object classes using a linear SVM (Support Vector Machine) for each class.
This implementation uses the Faster R-CNN architecture proposed by Shaoqing Ren et al. in their paper, "Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks". Faster R-CNN replaces the selective search algorithm with a Region Proposal Network (RPN), which is trained end-to-end with the object detection network.

### Installation
Clone this repository:
git clone https://github.com/XunQAQ/R-cnn-Object-Detection.git
