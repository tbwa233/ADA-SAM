# ADA-SAM
This repository contains the implementation of ADA-SAM. Our publications for this project are listed below:

Our proposed model performs joint semi-supervised classification and segmentation by employs a novel gradient feedback mechanism which forms a learnable connection between segmentation and classification branches by using the segmentation gradients to guide and improve the classification predictions.

## Abstract
Medical image segmentation is a key task in the imaging workflow, influencing many image-based decisions. Traditional, fully-supervised segmentation models rely on large amounts of labeled training data, typically obtained through manual annotation, which can be an expensive, time-consuming, and error-prone process. This signals a need for accurate, automatic, and annotation-efficient methods of training these models. We propose ADA-SAM (automated, domain-specific, and adaptive segment anything model), a novel multitask learning framework for medical image segmentation that leverages class activation maps from an auxiliary classifier to guide the predictions of the semi-supervised segmentation branch, which is based on the Segment Anything (SAM) framework. Additionally, our ADA-SAM model employs a novel gradient feedback mechanism to create a learnable connection between the segmentation and classification branches by using the segmentation gradients to guide and improve the classification predictions. We validate ADA-SAM on real-world clinical data collected during rehabilitation trials, and demonstrate that our proposed method outperforms both fully-supervised and semi-supervised baselines by double digits in limited label settings.

## Model
![Figure](https://github.com/tbwa233/ADA-SAM/blob/main/images/adasamarch.png?raw=true)
