# Biodiversity Sensor - Species Identification
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/syngenta/BiodiversitySensorProject_SpeciesIdentificationCode/blob/main/train_yolov5.ipynb)

## Overview
Species Identification is an open-source repository that's part of Syngenta's Biodiversity Sensor Project. 
This document describes how a YOLOv5-based architecture could be used to tackle the challenge of detecting 
insect species from remotely captured images and presents the results achieved from it. Additionally, it 
includes a runnable example with detailed instructions for reproduction.

## Dataset
In the initial phase of the research, a comprehensive dataset was generated using internet images sourced 
from iNaturalist and GBIF. As the project progressed, new images obtained during field deployment were added 
iteratively to enhance the robustness of the model.

### Field Data Annotation Process
To enhance the efficiency of the data annotation process, [Roboflow](https://docs.roboflow.com/) was utilized. 
This web-based platform is designed to streamline the management, augmentation, and labeling of datasets for computer 
vision tasks. By leveraging insights from previously trained models, Roboflow significantly accelerated 
the annotation workflow of the additional images.

## Model
The attached script provides a clear overview of the steps to create a YOLOv5 model, from training to image 
detection. For detailed information, the full documentation is available on the [Ultralytics YOLOv5 webpage](https://docs.ultralytics.com/yolov5/).

## Results