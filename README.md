# Crop-Classification-using-Deep-Learning-Models

This repository focuses on fusing Sentinel-1 Synthetic Aperture Radar (SAR) and Sentinel-2 optical datasets for classification tasks using advanced machine learning and deep learning models. The workflow includes preprocessing, data fusion, and classification.

Key Features
Preprocessing: Co-registration and resampling of SAR and optical datasets to ensure spatial alignment.
Data Fusion: Merging SAR and optical bands into multi-band GeoTIFF files.
Classification: Training and inference using CNN, ANN, and Random Forest classifiers.
Workflow
Preprocessing: Align and resample datasets.
Fusion: Concatenate SAR and optical data.
Classification: Train CNN, ANN, or Random Forest models to classify fused data.
Requirements
Python 3.8+
Key Libraries: GDAL, NumPy, TensorFlow, PyTorch, Scikit-learn, Matplotlib
Sentinel datasets (download from Copernicus Hub)
