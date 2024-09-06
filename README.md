# AstroExplorer

AstroExplorer is a project aimed at automating the classification and enhancement of astronomical objects using machine learning. Given the massive influx of data from modern telescopes, this tool classifies astronomical objects such as galaxies, stars, and quasars, while also applying specific image enhancement techniques tailored to each object type.

## Overview

AstroExplorer addresses the challenge of classifying astronomical objects from FITS images and light curves through a machine learning pipeline. The project consists of three main components:

1.  **Data Collection**: Curation and processing of astronomical datasets.
2.  **Image and Light Curve Classification**: Use of CNN and DNN architectures for object classification.
3.  **Image Enhancement**: Application of enhancement techniques to improve image visibility based on object type.

## Dataset 
Image Classification has dataset at https://drive.google.com/drive/folders/17d-vapkD364ZbqPHHlxHbm9Byld201i-?usp=sharing
The X.npy is the entire dataset which contains all the fits files and y_exp1.npy contains the target ids.
Light Curve Classification has dataset at https://drive.google.com/drive/folders/1xb_yZ3qELf4z6twzZBEmkPeW8niw_RrR?usp=sharing
combined_light_curve_data is the csv file that has the dataset of light curves with columns of mjd, flux and flux_error

## Features

-   **Astronomical Object Classification**: Utilizes a CNN-based model to classify galaxies, stars, and quasars.
-   **Image Enhancement**: Automatically enhances astronomical images by combining multiple spectral bands to improve visibility.
-   **Light Curve Classification**: Uses LSTM networks to classify variable stars based on their light curves.

## Challenges

-   **Data Handling**: Large datasets require efficient memory management.
-   **Model Optimization**: Overfitting and computational resource constraints were addressed through regularization techniques and GPU optimization.
-   **Sequence Padding**: Properly padding variable-length light curves for the LSTM model was a challenge. 	
## Pre-trained Saved Models
These models are uploaded on github.
The model.h5 file is for Light Curve Classification and is uploaded on the Github.
The CNN_Classifier.h5 file is uploaded on the link https://drive.google.com/drive/folders/17d-vapkD364ZbqPHHlxHbm9Byld201i-?usp=sharing with the dataset.

* Due to time constraint and github error we have uploaded model also on google drive. Link is shared.

### Details of what the dataset contains and the code flow is available in the documentation file
