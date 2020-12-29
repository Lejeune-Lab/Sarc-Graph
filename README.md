# Sarc-Graph
Segmentation, tracking, and analysis of sarcomeres in hiPSC-CMs

# Data

## Synthetic data

The synthetic data (synthetic_data_1, synthetic_data_2, and synthetic_data_3) are generated with the included scripts:

`geom_fcns.py`- Define a baseline geometry of sarcomere chains. 

`render_fcns.py` - Render the baseline geometry as a two dimensional movie. 

`synthetic_data_1.py`:
https://github.com/elejeune11/Sarc-Graph/blob/main/ALL_MOVIES_RAW/synthetic_data_1/frame_000.png

`synthetic_data_2.py`:
https://github.com/elejeune11/Sarc-Graph/blob/main/ALL_MOVIES_RAW/synthetic_data_2/frame_000.png

`synthetic_data_3.py`:
https://github.com/elejeune11/Sarc-Graph/blob/main/ALL_MOVIES_RAW/synthetic_data_3/frame_000.png

## Real data

The real data (real_data_Sample_1 and real_data_Sample_2) was originally published with the paper ``An Adaptable Software Tool for Efficient Large-Scale Analysis of Sarcomere Function in hiPSC-Cardiomyocytes'' found at https://www.ahajournals.org/doi/full/10.1161/CIRCRESAHA.118.314505 . 

# Code

## Python packages
All code is written in python -- the following packages are required:
* av
* collections
* csv
* cv2
* glob
* imageio
* matplotlib
* networkx
* numpy
* os 
* pandas
* pickle
* PIL 
* scipy
* skimage
* sklearn.gaussian_process
* sys
* trackpy

## Scripts


