# Crop-Classification-using-Deep-Learning-Models

This project focuses on crop classification by fusing Sentinel-1 SAR and Sentinel-2 optical satellite imagery, using Deep Learning and Machine Learning techniques. The objective is to accurately classify crop types based on multi-source remote sensing data.

**Objective**

To build a robust model that can classify different types of crops (e.g., Wheat 1, Wheat 2, Onion, Garlic) using fused satellite imagery and evaluate the performance of various models including CNN, ANN, RNN, and Random Forest.

**Dataset Description**

Satellite Data Sources:
Sentinel-1 (SAR) and Sentinel-2 (Optical) images were obtained from the Copernicus Open Access Hub.

Study Area: Indore City, India (specifically the Mhow Road, Simrol region).
Crop Shapefile: Provided labeled ground truth data for four crop types.

**Workflow**

Data Collection
Downloaded Sentinel-1 and Sentinel-2 images.
Obtained crop shapefiles for ground truth labels.

Preprocessing
Used SNAP and QGIS for:
Radiometric and geometric corrections
Geocoding and co-registration
Clipping and aligning datasets

Feature Extraction and Fusion
Merged SAR and optical features.
Created fused multi-band images for classification.
Model Training
Python libraries used: TensorFlow, Keras, Scikit-learn, Geopandas, Rasterio

**Models Implemented:**

Random Forest
Convolutional Neural Network (CNN)
Artificial Neural Network (ANN)
Recurrent Neural Network (RNN)

**Evaluation**

Accuracy of each model was measured and compared.
Random Forest achieved 95%, while CNN-based data fusion yielded the highest deep learning accuracy of 61%.

**Results**
Model	Accuracy
Random Forest	95%
CNN (Fusion Model)	61%
ANN	~57%
RNN	~54%

**Project Structure**
graphql
Copy
Edit
Crop-Classification/
│
├── data/                  # Satellite and shapefile data
├── preprocessing/         # SNAP and QGIS preprocessing scripts
├── models/                # Trained ML/DL models
├── notebooks/             # Jupyter notebooks for training/testing
├── results/               # Accuracy reports and plots
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation

**Tools and Technologies**
Python, TensorFlow, Keras, Scikit-learn, Rasterio, Geopandas
SNAP (Sentinel Application Platform), QGIS
Jupyter Notebooks, Pandas, Matplotlib

**Future Work**
Explore Transformer-based models on fused imagery
Incorporate attention mechanisms to enhance spatial feature learning
Extend classification to time-series analysis for monitoring crop cycles

**Author**
Rishika Nigam
B.Tech, Mechanical Engineering, Birla Institute of Technology, Mesra
Email: rishikanigam4@gmail.com
LinkedIn: Rishika Nigam


