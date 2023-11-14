# Materials for "Machine learning for spatial data"

## Course goals
 * General overview of machine learning for spatial data
 * Give vocabulary to continue with own experiments
 * Show and run some practical examples



## Content of this repository

This repository contains all Jupyter Notebooks and other code used in the course. Data is not inlcuded here, data download links are provided in data preparations Notebooks. Each exercise has its own folder:

* [01_clustering](01_clustering) 
* [02_vector_data_preparation](02_vector_data_preparation)
* [03_raster_data_preparation](03_raster_data_preparation)
* [04_shallow_regression](04_shallow_regression)
* [05_shallow_classification](05_shallow_classification)
* [06_deep_regression](06_deep_regression)
* [07_deep_classification](07_deep_classification)
* [08_cnn_segmentation](08_cnn_segmentation)



## Exercises on own computer

Exercises Jupyter notebooks can be run as is on any computer. 
To get started:
* Get the exercise material from Github
	* Clone this Github repository: `git clone https://github.com/csc-training/GeoML.git` 
	* OR download the repository as a [zip-file](https://github.com/csc-training/GeoML/archive/refs/heads/main.zip)
* Install all needed packages for running the notebooks:
	* For pip use the [requirements.txt](requirements.txt) with `pip install -e requirements.txt`
	* OR for conda, use the [environment.yml](environment.yml) with `conda create --name geoml --file environment.yml` which also creates a conda environment; see [conda homepage](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html#managing-envs) on how to use it). 

* Adapt the main path in beginning of each notebook to your environment.
* Have fun going through the notebooks and add an issue to this repository if something is not working.
#### Jupyter 


#### QGIS
## Extra material

* [Links to further resources](links.md)
* [Optional tools for machine learning with spatial data](tools.md)


