# TFG_surface_temp_model
Convolutional Autoencoder for climate data compression

The objective of this work was to analyze the use of Deep Learning models (CNN autoencoders) on climate data as an alternative lossy compression technique, 
 using quality metrics (Baker-2014) to ensure an appropriate reconstruction of the original data.

The NCEP/NCAR Reanalysis 1 project is using a state-of-the-art analysis/forecast system to perform data assimilation using past data from 1948 to the present

<p align="center">
<img src="https://github.com/dbeniteze/TFG_surface_temp_model/blob/main/figures/mapa_surf.png" width="275">
</p>

### Dataset

Spatial Coverage : 2.5 degree x 2.5 degree global grids (144x73). 0.0E to 357.5E, 90.0N to 90.0S

Training set : 
 - Daily surface temperature (0.995sigma) data from 1948 to 2020.
 
Test set:
 - 20% of training set

Evaluation set:
 - Daily surface temperatures from 2021

### Encoder Architecture

<p align="center">
<img src="https://github.com/dbeniteze/TFG_surface_temp_model/blob/main/figures/esquema_encoder.png" width="500">
</p>

### Encoder Architecture

<p align="center">
<img src="https://github.com/dbeniteze/TFG_surface_temp_model/blob/main/figures/esquema_decoder.png" width="500">
</p>

### References:

<a href="https://psl.noaa.gov/data/gridded/data.ncep.reanalysis.html"> NCEP-NCAR Reanalysis 1 </a>


}Baker et al. - 2014 - A Methodology for Evaluating the Impact of Data Compression on Climate Simulation Data-annotated

Baker et al. - 2016 - Evaluating lossy data compression on climate simulation data within a large ensemble-annotated

Baker et al. - 2017 - Toward a Multi-method Approach: Lossy Data Compression for Climate Simulation Data
