# LIDC-IDRI-Image-Anomaly-Detection
This repository would preprocess, segment and extract features from the LIDC-IDRI dataset to create a machine learning algorithm able to determine if a lung image is "normal" or anomalous. This is done by applying a gabor filter to enhance the image, then a watershed segmentation which will be helpful during feature extraction.

* +-- Datasets
|    # This file contains the original LIDC dataset
* +-- Data
|    # This file contains the preprocessed data
* +-- Processed
|    # This file contains the processed data for training
* +-- Segmented
|    # This file contains the feature extraction code and and Meta for the model
* +-- Layout
|    # This file contains the code used to display the code
