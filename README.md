## Reconstruction of Surface Dynamics from Sea Surface Height Using Neural Network
### Qiyu Xiao, Dhruv Balwada, C. Spencer Jones, Mario Herrero-Gonz ́alez, K. Shafer Smith, Ryan Abernathey

This repository contains all jupyter notebooks that are needed to redo the analysis presented in this paper. Versions of important python packages used in this project are: Xarray - 0.17.0, Pytorch - 1.10.1, Numpy - 1.19.2, xhistogram - 0.3.2, matplotlib - 3.6.0, xgcm - 0.8.0, scipy - 1.9.1.

The CNN model setup and training is shown in model_example.ipynb. In figure 5.ipynb we use figure 5 as an example to show how we make plots in X-Y plane and how we calculate and plot vorticity-strain joint distributions. In figure 8.ipynb we use figure 8 as an example to show how to apply a trained model to reconstruct vorticity in the test region. In figure 19 we show how to calculate CKA used in figure 19.

Regarding data used in this paper, both the [channel simulation](https://catalog.pangeo.io/browse/master/ocean/channel/channel_ridge_resolutions_01km/) and [LLC4320](https://catalog.pangeo.io/browse/master/ocean/LLC4320/) are accessible through [Pangeo](https://pangeo.io/). The synthetic internal waves data is generated using matlab package [GLOceanKit](https://github.com/Energy-Pathways-Group/GLOceanKit). 

