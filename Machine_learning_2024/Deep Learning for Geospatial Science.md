# Deep Learning for Geospatial Science Workshop

**Duration**: 2 Hours  
Research Computing Center - GIS  
*Presenter: Parmanand Sinha*

---

# Slide 1: Workshop Overview

- **Objective**: Introduce core ML concepts in geospatial science and apply deep learning to spatial data.
- **Topics**: ML fundamentals, geospatial clustering, classification, and regression.
- **Hands-on**: Classification and clustering with practical geospatial datasets.

*Image*: Overview of Deep Learning Applications in GIS (Source: Esri [2023](https://www.esri.com/en-us/arcgis/products/deep-learning/overview))

---

# Slide 2: What is Machine Learning?

- Study of algorithms that learn from data patterns instead of hard-coded rules.
- Goal: **Generalization** – making accurate predictions on unseen data.
- Key in spatial science: recognizing geospatial patterns for prediction.

*Image*: Basic ML Flowchart (Source: [Wikipedia](https://en.wikipedia.org/wiki/Machine_learning))

---

# Slide 3: Data in Machine Learning

1. **Numerical Data**: Often structured in matrix format.
2. **Design Matrix**: Rows represent data samples, columns are features.
3. Example: *Iris Dataset* with features like petal length and width.

*Image*: Data Matrix Representation (Source: [Kaggle](https://www.kaggle.com/))

---

# Slide 4: Types of Machine Learning

- **Supervised Learning**: Uses labeled data (e.g., land cover classification).
- **Unsupervised Learning**: Works with unlabeled data (e.g., clustering).
- **Reinforcement Learning**: Trains models based on feedback and rewards.

*Image*: Types of ML (Source: Towards Data Science [2023](https://towardsdatascience.com/))

---

# Slide 5: Supervised Learning

- Goal: Learn a mapping from input `(x)` to output `(y)` (label).
- **Classification**: Categorical output, e.g., urban vs. rural.
- **Regression**: Continuous output, e.g., temperature prediction.

*Image*: Supervised Learning Process (Source: [Scikit-learn](https://scikit-learn.org/))

---

# Slide 6: Unsupervised Learning

- No labeled data; goal is to find hidden structure.
- Applications: Clustering for segmentation or anomaly detection.

*Image*: Unsupervised Clustering Example (Source: [Esri](https://www.esri.com/))

---

# Slide 7: Model Training and Inference

- **Training**: Adjust model parameters to minimize error.
- **Inference**: Apply trained model to classify or predict on new data.
- Use cases: Land cover classification and urban mapping.

*Image*: Model Training Diagram (Source: [PyTorch](https://pytorch.org/))

---

# Slide 8: Optimization and Gradient Descent

- **Gradient Descent (GD)**: Algorithm for minimizing loss.
- **Learning Rate**: Step size during optimization.
- **SGD**: Processes data in batches, faster for large datasets.

*Image*: Gradient Descent Visualization (Source: Towards Data Science [2023](https://towardsdatascience.com/))

---

# Slide 9: Overfitting vs. Underfitting

- **Overfitting**: Model memorizes training data, poor generalization.
- **Underfitting**: Model too simple to capture patterns.
- **Regularization**: Techniques to reduce overfitting (dropout, early stopping).

*Image*: Overfitting and Underfitting Curves (Source: [Scikit-learn](https://scikit-learn.org/))

---

# Slide 10: Training, Validation, and Testing

1. **Training Set**: Used to learn model parameters.
2. **Validation Set**: For tuning model hyperparameters.
3. **Test Set**: Final evaluation of model performance.

*Image*: Data Split Diagram (Source: Towards Data Science [2023](https://towardsdatascience.com/))

---

# Slide 11: Classification

- Predicts a **categorical output** like urban/rural.
- Use Cases: Vegetation classification, land cover mapping.
- Types: Binary, Multi-class, Multi-label.

*Image*: Classification Example (Source: [Esri](https://www.esri.com/))

---

# Slide 12: Common Types of Classification

1. **Binary**: Two classes (e.g., forest vs. non-forest).
2. **Multi-class**: Multiple classes (e.g., land types).
3. **Multi-label**: Predict multiple categories per instance.

*Image*: Binary and Multi-class Examples (Source: [Scikit-learn](https://scikit-learn.org/))

---

# Slide 13: MNIST - Handwritten Digit Classification

- Dataset: 70,000 images of handwritten digits (0–9).
- Example of multi-class classification.
- Widely used for ML model benchmarking.

*Image*: MNIST Digit Examples (Source: [MNIST Database](http://yann.lecun.com/exdb/mnist/))

---

# Slide 14: Classification Metrics

1. **Accuracy**: Correct predictions over total predictions.
2. **Precision**: Focuses on positive-predicted classes.
3. **Recall**: Focuses on finding all actual positives.

*Image*: Confusion Matrix for Classification (Source: [Wikipedia](https://en.wikipedia.org/wiki/Confusion_matrix))

---

# Slide 15: Confusion Matrix

- Rows represent true classes, columns represent predicted.
- Useful for analyzing model performance and error types.

*Image*: Confusion Matrix Example (Source: Towards Data Science [2023](https://towardsdatascience.com/))

---

# Slide 16: Regression

- Predicts a **numerical** outcome like house prices or temperature.
- Use Cases: Predicting NDVI, land surface temperature, etc.

*Image*: Regression Example (Source: [Scikit-learn](https://scikit-learn.org/))

---

# Slide 17: Linear Regression

- **Simple Model**: Predicts output based on linear relationship.
- Variants: Ridge, Lasso, Elastic Net (add constraints).

*Image*: Linear Regression Line (Source: [Kaggle](https://www.kaggle.com/))

---

# Slide 18: Nonlinear Regression

- For data not well-modeled by a linear approach.
- Polynomial regression is a common nonlinear method.

*Image*: Polynomial Regression Fit (Source: Towards Data Science [2023](https://towardsdatascience.com/))

---

# Slide 19: Regression Metrics

1. **Mean Absolute Error (MAE)**
2. **Mean Squared Error (MSE)**
3. **R-Squared (R²)**

*Image*: MSE and MAE Formulae (Source: [Scikit-learn](https://scikit-learn.org/))

---

# Slide 20: Clustering

- Group similar data points without labels.
- Use Cases: Land cover mapping, segmentation, cloud detection.
- Common Algorithms: K-means, DBSCAN.

*Image*: Clustering Example with K-means (Source: [Wikipedia](https://en.wikipedia.org/wiki/K-means_clustering))

---

# Slide 21: K-means Clustering

- Partitions data into k clusters based on variance.
- Objective: Minimize within-cluster sum of squares.

*Image*: K-means with Centroids (Source: [Scikit-learn](https://scikit-learn.org/))

---

# Slide 22: Geospatial Clustering Examples

- **Land Cover Classification**: Urban vs rural areas.
- **Cloud Detection**: Differentiate clouds from land/water.
  
*Image*: Satellite Image Segmentation (Source: [Esri](https://www.esri.com/))

---

# Slide 23: Practical Hands-on Clustering

*Notebook Exercise*: Hands-on clustering analysis with K-means on spatial data.

*Image*: Clustering Demo in Notebook (Source: Custom content)

---

# Slide 24: Deep Learning in Geospatial Analysis

- **ArcGIS Learn**: Tools for geospatial deep learning.
- Applications: Building footprint extraction, vegetation analysis, etc.

*Image*: Deep Learning Workflow in ArcGIS (Source: Esri [2023](https://www.esri.com/))

---

# Slide 25: Tools and Frameworks for GeoAI

1. **TorchGeo**: Datasets and samplers for spatial data in PyTorch.
2. **ArcGIS.learn**: Streamlined workflows for GIS applications.
3. **GDAL & Rasterio**: Data handling libraries for geospatial formats.

*Image*: GeoAI Toolkits Overview (Source: [Esri](https://www.esri.com/))

---

# Slide 26: Hands-on Example - Land Cover Classification

*Notebook Exercise*: Use TorchGeo and ArcGIS.learn to build and train a model for land cover classification.

*Image*: Land Cover Map from Model (Source: [NASA EarthData](https://earthdata.nasa.gov/))

---

# Slide 27: Object Detection in Geospatial Data

- Detecting objects like buildings, roads in satellite imagery.
- Applications: Mapping infrastructure, disaster assessment.

*Image*: Object Detection Example (Source: [Esri](https://www.esri.com/))

---

# Slide 28: Model Evaluation

1. **Accuracy and Precision**: Assess correctness of predictions.
2. **Confusion Matrix**: Analyze and address misclassifications.

*Image*: Example of Model Evaluation Metrics (Source: [Scikit-learn](https://scikit-learn.org/))

