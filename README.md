# MTFI_short
$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$
## Overview
This is the source code and summary of datasets used for the short paper, which aims to investigate and model the relationship between characteristics of traffic infrastructure and the presence of e-scooter accidents, with a focus on curb and complexity of street views.
$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$
## Table of Contents
### [Data & Software](#data-and-software)
### [Functions](#mtp_function_yl)
### Workflow
Preproccessing and image data preparation
- [Obtain Google Street View Images](#work_01_googlestreetviewimages_processing) 
  
Image segmentation and calculation of mask properties
- [Apply Segment Anything Model(SAM) and filtering output masks](#work_02_imagesegmentation_maskfiltering)
- [Detect contours and calculate mask properties](#work_03_contourdetection_maskpropertiescalculation)
- [Interpret masks and label](#work_04_maskinterpretationandlabelling)
- [Statistical analysis of mask properties](#work_05_maskpropertiesstatisticsdistribution)

Generation of Pseudo-absence points and processing image data
- [Obtain GSV images of pseudo-absence points, apply SAM, calculate mask properties](#work_06_randompseudopoints_gsvimages_segmentation_maskfiltering)

Construction of classification models
- [Build classification models](#work_07_buildingclassificationmodel_curbextraction_entropycalculation)
- [Apply classification models to extract curbs and calculate entropy values](#work_08_maskpropertiescalculation_entropycalculation)

Preparation of variables
- [Prepare curb-related variables and entropy variables](#work_09_variablespreparation_curbrelated_entropyvariables)
- [Prepare traffic transport infrastructure variables](#work_10_variablespreparation_traffictransportinfrastructurevariables)
- [Variables transformation](#work_11_variablestransformation)

Modelling
- [Logistic regression analysis and random forest classification](#work_12_modellingpresenceofaccident)

Data Visualization
- [Map and illustration](#work_13_datavisualization_illustrationfigures)

$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$
## Data and Software
- Data sources:
    - Google Street View Images, accessed through static API by the [Google Maps Platform](https://developers.google.com/maps/documentation/streetview/overview).
    - Traffic, transport and infrastructure datasets, obtained from [Open Data Zurich](https://data.stadt-zuerich.ch/).
- Model application:
    - [Segment Anything Model](https://github.com/facebookresearch/segment-anything).
- Software used for data preprocessing:
    - [QGIS](https://qgis.org/project/overview/)
- Python packages
    - [pytorch](https://pytorch.org/)
    - [opencv](https://pypi.org/project/opencv-python/)
    - [numpy](https://numpy.org/)
    - [mlxtend](https://rasbt.github.io/mlxtend/)
    - [pandas](https://pandas.pydata.org/)
    - [matplotlib](https://matplotlib.org/)
    - [seaborn](https://seaborn.pydata.org/)
    - [shapely](https://shapely.readthedocs.io/en/stable/)
    - [sklearn](https://scikit-learn.org/stable/)
    - [scipy](https://scipy.org/)
    - [category_encoders](https://pypi.org/project/category-encoders/)
    - [joblib](https://joblib.readthedocs.io/en/stable/)
    - [pyproj](https://pyproj4.github.io/pyproj/stable/)
    - [PIL](https://pypi.org/project/pillow/)
    - [statsmodels](https://www.statsmodels.org/stable/index.html)

## Scripts


#### Work_01_GoogleStreetViewImages_Processing



#### Work_02_ImageSegmentation_MaskFiltering
#### Work_03_ContourDetection_MaskPropertiesCalculation
#### Work_04_MaskInterpretationandLabelling
#### Work_05_MaskPropertiesStatisticsDistribution

#### Work_06_RandomPseudoPoints_GSVImages_Segmentation_MaskFiltering

#### Work_07_BuildingClassificationModel_CurbExtraction_EntropyCalculation
#### Work_08_MaskPropertiesCalculation_EntropyCalculation

#### Work_09_VariablesPreparation_CurbRelated_EntropyVariables
#### Work_10_VariablesPreparation_TrafficTransportInfrastructureVariables
#### Work_11_VariablesTransformation

#### Work_12_ModellingPresenceofAccident

#### Work_13_DataVisualization_IllustrationFigures



#### mtp_function_yl







$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$

## Requirement



$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$

## Links





