## Reconstruction of Surface Dynamics from Sea Surface Height Using Neural Network
### Qiyu Xiao, Dhruv Balwada, C. Spencer Jones, Mario Herrero-Gonz ́alez, K. Shafer Smith, Ryan Abernathey

This repository contains all jupyter notebooks that are needed to redo the analysis presented in this paper. Versions of important python packages used in this project are: Xarray - 0.17.0, Pytorch - 1.10.1, Numpy - 1.19.2, xhistogram - 0.3.2, matplotlib - 3.6.0, xgcm - 0.8.0, scipy - 1.9.1.

The CNN model setup and training is shown in model_example.ipynb. In [figure_2.ipynb](figure_2.ipynb) we use figure 2 as an example to show how we make plots in X-Y plane and how we calculate and plot vorticity-strain joint distributions. The same code also applies to the making of figure 1, 3, 4, 5, 8, 10.

In [model_example.ipynb](model_example.ipynb) we shows the code we use for preprocessing data and training a Unet. In [figure_7.ipynb](figure_7.ipynb) we use figure 7 as an example to show how to apply a trained model to reconstruct vorticity in the test region. Both these codes also apply to the making of figure 9, 10, 11, 12, 13, 14, 15.

In [figure_17.ipynb](figure_17.ipynb) we show how to calculate CKA used in figure 17.

Regarding data used in this paper, both the [channel simulation](https://catalog.pangeo.io/browse/master/ocean/channel/channel_ridge_resolutions_01km/) and [LLC4320](https://catalog.pangeo.io/browse/master/ocean/LLC4320/) are accessible through [Pangeo](https://pangeo.io/). The synthetic internal waves data is generated using matlab package [GLOceanKit](https://github.com/Energy-Pathways-Group/GLOceanKit). 

