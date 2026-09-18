\# UrbanScan AI



AI-based urban analysis of Khankandi using satellite imagery.



\## Overview



UrbanScan AI is a remote sensing and artificial intelligence project designed to analyze urban development and environmental changes in Khankandi using multi-source satellite and geospatial data.



The project combines high-resolution Azersky imagery, ESA Sentinel-2 satellite data, and SRTM digital elevation data to investigate land cover, urban expansion, vegetation, terrain characteristics, construction suitability, solar potential, and accessibility.



\## Objectives



\* Classify the urban area into major land-cover categories

\* Detect infrastructure and urban development changes over time

\* Analyze vegetation using NDVI

\* Evaluate terrain, slope, and hydrological characteristics

\* Identify areas suitable for future construction

\* Assess solar energy potential

\* Estimate vegetation-based carbon storage

\* Analyze accessibility using the 15-minute city concept

\* Project potential urban expansion toward 2030



\## Data Sources



\* Azersky — high-resolution RGB satellite imagery

\* Sentinel-2 L2A — multispectral satellite imagery

\* SRTM — digital elevation model



\## Methodology



The analysis includes:



1\. Satellite image preprocessing and normalization

2\. NDVI calculation for vegetation analysis

3\. Land-cover classification using Random Forest

4\. Multi-temporal urban change detection

5\. Terrain and slope analysis

6\. MCDA-based construction suitability analysis

7\. Solar potential assessment

8\. Carbon storage estimation

9\. 15-minute accessibility analysis

10\. Urban expansion projection for 2030



\### Land-cover classes



The classification model identifies five main classes:



\* Dense vegetation

\* Sparse vegetation

\* Built-up areas

\* Red roofs

\* Bare soil



\### Machine Learning



A Random Forest classifier with 300 trees was used for land-cover classification.



The model was evaluated using 5-fold cross-validation.



\## Results



The analysis produced indicators related to:



\* Existing built-up area

\* New construction and urban expansion

\* Vegetation change

\* Carbon storage

\* Solar potential

\* Flood-risk areas

\* Walking accessibility

\* Projected 2030 built-up area



The classification achieved an overall accuracy of approximately 63.1% with a Kappa coefficient of 0.385.



Detailed results and visualizations are available in the Jupyter Notebook.



\## Technologies



\* Python 3.12

\* Google Colab

\* NumPy

\* Rasterio

\* SciPy

\* scikit-learn

\* Matplotlib

\* PyProj

\* Streamlit



\## Repository Structure



```text

UrbanScan-AI/

│

├── azercosmos\_layihe.ipynb

├── .gitignore

└── README.md

```



\## Notebook



The main analysis is contained in:



`azercosmos\_layihe.ipynb`



The notebook was developed in Google Colab and uses satellite and geospatial datasets stored separately from this repository.



\## Future Development



Planned extensions include:



\* Interactive Streamlit web platform

\* Improved land-cover classification

\* Additional temporal satellite imagery

\* More advanced urban-growth modelling

\* Interactive maps and spatial visualizations

\* Integration of additional urban planning indicators



\## Project



UrbanScan AI

AI-based urban monitoring and spatial analysis using satellite imagery.

