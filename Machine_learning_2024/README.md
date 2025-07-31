# Deep Learning for Geospatial Science Workshop

## Overview
Welcome to the **Deep Learning for Geospatial Science Workshop** repository! This repository contains materials for a two-hour hands-on workshop on applying machine learning and deep learning techniques to geospatial data. Participants will explore various machine learning methods and complete practical exercises on clustering, classification, and object detection using tools such as TorchGeo and ArcGIS.learn.

## Contents
- **Presentation Slides**: An introduction to machine learning and deep learning concepts, tailored to geospatial applications.
- **Notebooks**:
  - `01_clustering.ipynb`: Practical notebook for clustering geospatial data using K-means.
  - `02_land_cover_classification.ipynb`: A hands-on notebook for land cover classification using TorchGeo and ArcGIS.learn.
  - `03_object_detection.ipynb`: Notebook for object detection in satellite imagery.
- **Data Samples**: Small datasets to be used with the notebooks (available upon request).

## Requirements
- **Python** 3.8+
- **Packages**: `torch`, `torchgeo`, `arcgis`, `gdal`, `rasterio`, `geopandas`
- Install packages with:
  ```bash
  pip install torch torchvision torchgeo arcgis gdal rasterio geopandas


Usage
Clone this repository:

git clone https://github.com/rcc-uchicago/Geocomputation_workshop


    ├── datasets/
    ├── notebooks/
    │   ├── land_cover_classification.ipynb
    │   └── object_detection_arcgis.ipynb
    ├── images/


### 1. **Datasets Directory** (`datasets/`):
   - **Land Cover Classification Dataset**: You can use datasets like *LandCover.ai* or *EuroSAT*, both of which are popular for land cover classification tasks.
     - **LandCover.ai**: [LandCover.ai Dataset](https://landcover.ai/) contains high-resolution aerial images for land cover classification.
     - **EuroSAT**: [EuroSAT on Kaggle](https://www.kaggle.com/datasets/apollo2506/eurosat) includes Sentinel-2 satellite images for land cover classification.
   - **Object Detection Dataset**: You could use datasets like *xView* or *SpaceNet* for building and object detection.
     - **xView**: [xView Dataset](https://xviewdataset.org/) for object detection in satellite imagery.
     - **SpaceNet**: [SpaceNet](https://spacenet.ai/) provides a variety of labeled satellite imagery for different tasks, including building footprint extraction.

### 2. **Notebooks Directory** (`notebooks/`):
   - **land_cover_classification.ipynb**: Customize a notebook with code to perform land cover classification using models from ArcGIS.learn or TorchGeo. You can adapt publicly available notebooks like the [ArcGIS Python API sample notebooks](https://developers.arcgis.com/python/sample-notebooks/).
   - **object_detection_arcgis.ipynb**: For object detection, refer to tutorials in the ArcGIS.learn library or ArcGIS [Object Detection Tutorial](https://developers.arcgis.com/python/guide/performing-object-detection-on-imagery/).

### 3. **Images Directory** (`images/`):
   - Store visuals such as workflow diagrams, example outputs, and confusion matrices used in the notebooks. 
 




