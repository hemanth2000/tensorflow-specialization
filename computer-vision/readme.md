# Notes on Advanced Computer Vision

# Introduction

Computer Vision (CV) is a field of Artificial Intelligence (A.I) that solves problems related to digital images. There are different kinds of CV problems such as Binary classification, Multi-class classification, Multi-label classification, Object localization, Object detection, Semantic segmentation, Instance segmentation. It is important to know the difference among these problems.

# Classfication problems

## Binary vs Multiclass vs Multi-label classification

The famous dog/cat classfication problem is a classic example of Binary classification problem. There are only two classes and typically sigmoid activation is used in the final layer of the CNN. If there are more than two classes then the problem is multiclass classification. Softmax activation is used at the final layer which gives probabilitiy of the each class for a single input. Typically, every input has only one class as the output. In case of multilabel classification, a single image has more than one class. 

## Object localization vs detection

Object localization is finding the object and its location in the image. Object detection involves finding multiple objects and their locations.

## Image Segmentation
In image segementation, every pixel is classified into classes. There are two types of Image Segmentation problems, Semantic and Instance segmentation. Semantic segmentation doesn't differentiate between the instances of the same kind. For example, all people are in an image is classified with same class in semantic segmentation in contrary each people is classified with different class in instance segmentation.


# Transfer Learning

