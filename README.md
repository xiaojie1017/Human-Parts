# Detector-in-Detector: Multi-Level Analysis for Human-Parts (ACCV'2018)
By Xiaojie Li, Lu Yang, Qing Song, Fuqiang Zhou

This project provides the Human-Parts dataset used in DID-Net.

![datasets](https://github.com/fwang91/IMDb-Face/blob/master/imdb-face.png)
Vision-based person, hand or face detection approaches have achieved incredible success in recent years with the development of deep convolutional neural network (CNN). We take the inherent correlation between the body and body parts into account and propose a new framework to boost up the detection performance of the multi-level objects. In particular, we adopt region-based object detection structure with two carefully designed detectors to separately pay attention to the human body and body parts in a coarse-to-fine manner, which we call Detector-in-Detector network (DID-Net). The framework is trained in an end-to-end way by optimizing a multi-task loss. Due to the lack of human body, face and hand detection dataset, we have collected and labeled a new large dataset named \textit{Human-Parts} with 14,962 images and 106,879 annotations. Experiments show that our method can achieve excellent performance on \textit{Human-Parts}.
