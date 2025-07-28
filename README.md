# Geomatics & Geoinformation – Remote Sensing Explorations
  
This repository brings together two reports developed during the course *Geomatics and Geoinformation* (MSc in Data Science – Sapienza University of Rome), but aims to be much more than an academic archive. It is a space where I explore how remote sensing, spectral indices, and classification algorithms can tell us stories about our planet.

So, this repository currently includes two independent yet complementary projects, both built with **Google Earth Engine** and real satellite imagery:

### 🌱 Handling spectral indices

In this project, I focused on the agricultural coast between *Fondi, Terracina, and Sperlonga*, known for its tomato (pomodorino) production. Using **Sentinel-2** and **Landsat-8** data, I computed:
- **NDVI** (Normalized Difference Vegetation Index)  
- **MNDWI** (Modified Normalized Difference Water Index)  
- A **greenest-pixel composite** to capture vegetation peaks
By comparing summer seasons (2022 vs 2023), I was able to quantify the dynamics of vegetation health and surface water availability, offering insight into irrigation practices and agricultural resilience.

📎 [Read the full report](./reports/GG_Tommasino_Report3.pdf)

### 🧠 Machine Learning with Google Earth Engine

In this second exploration, I tested how machine learning algorithms can be used to classify land cover types from satellite images. Across three regions (Scotland, Iceland, and Washington State), I implemented:
- K-means clustering (unsupervised)  
- Support Vector Machine (SVM), binary classification for snow detection  
- Random Forest, multiclass classification trained on ESA WorldCover data
Each method was tuned and validated using accuracy metrics and confusion matrices. The result is a practical overview of how well different classifiers handle real-world environmental data.

📎 [Read the full report](./reports/GG_Tommasino_Report6.pdf)
