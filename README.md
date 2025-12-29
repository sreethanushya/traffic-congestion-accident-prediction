# traffic-congestion-accident-prediction
Traffic congestion and accident prediction using ML and geospatial data
## Note on Dataset Paths
This project was developed and executed in Google Colab.
Datasets were accessed via Google Drive using Colab-specific paths.
To run the notebooks locally, users will need to update the dataset paths accordingly.
This project analyzes traffic congestion and accident severity by integrating
historical accident data with OpenStreetMap (OSM) road network data.

## Project Structure
- Data cleaning and preprocessing of large-scale accident data
- Conversion and feature extraction from OSM road data
- Spatial integration of accidents with nearest road segments
- Machine learning models for accident severity prediction

## Notebooks
- 01_cleaning.ipynb  
- 02_integrated_dataset_accident_congestion.ipynb  
- 03_implementaion.ipynb  

## Tech Stack
Python, Pandas, GeoPandas, OSMnx, Scikit-learn, XGBoost, TensorFlow, Folium

Data sources:
- US Accidents Dataset: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents
- OpenStreetMap data: https://download.geofabrik.de/
