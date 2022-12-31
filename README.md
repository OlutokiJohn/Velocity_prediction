# Velocity_Prediction

## Objectives
Velocity is one of the most important petrophysical parameters used in oil-field optimization or other geophysical surveys to easily determine and predict horizons, faults, facies, unconformities, stratigraphic boundaries, geologic structures, fluid contents, the knowledge of velocity at any depth is very important in the recognition of reflectors and refractors with dip or plane horizontal beds. 
This repo contains Jupyter notebooks to Predict Compressional and shear wave velocity using using well logs datas using machine learning models.
The workflow is typical for any similiar project and it entails: • Wrangle and process the data to the desired format; • Carry out quick look and statistical
analysis of the well log data; • Develop a model using a Decision Tree, Random forest and Linear Regression; and • Deploy the model and investigate its performance.

## Data Source
The geophysical logs used in this study are from the Ordos Basin. The data isn't made available through the open-source subsurface data.

## Implementation

__Software__: `Python`

__Packages__: `lasio`, `sklearn`, `numpy`, `pandas` and `matplotlib`

The various manipulations and operations on the well logs is done by running the jupyter notebook called `RF_P_wave.ipynb` and `RF_S_wave.ipynb`. 
