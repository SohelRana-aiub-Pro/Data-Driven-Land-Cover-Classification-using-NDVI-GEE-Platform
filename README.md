Data-Driven-Land-Cover-Classification-using-NDVI-GEE-Platform, A Case Study of Dhaka, Bangladesh.
-------------------------------------------------------------------------------------------------

<p align="center">
  <b>A Remote Sensing and Geospatial AI Approach for Automated Land Cover Mapping with Landsat 8 Time-Series Data</b>
</p>

---

Overview
---------------
**Data-Driven Land Cover Classification using NDVI & Google Earth Engine (GEE) Platform** is a remote sensing and geospatial analysis project that focuses on automated land cover mapping using satellite imagery, vegetation indices, and data-driven classification techniques.

The project utilizes **Landsat 8 time-series satellite imagery**, **Normalized Difference Vegetation Index (NDVI)** analysis, and the **Google Earth Engine (GEE)** cloud computing platform to classify different land cover types.

The primary study area is the **Dhaka Region, Bangladesh**, where rapid urbanization has caused significant changes in vegetation coverage, agricultural land, water bodies, and built-up areas.

This project demonstrates how satellite remote sensing, GIS techniques, and machine learning approaches can be combined for environmental monitoring, urban planning, and land-use change analysis.

---
Objectives
--------------
The main objectives of this project are:

* Analyze multi-temporal satellite imagery for land cover assessment.
* Generate NDVI maps from Landsat 8 satellite data.
* Identify vegetation characteristics using spectral information.
* Develop an automated land cover classification workflow.
* Classify land surfaces into different categories.
* Visualize spatial distribution of land cover classes.
* Demonstrate the capability of Google Earth Engine for large-scale geospatial analysis.

---

Study Area
---------------------
Dhaka Region, Bangladesh


Dhaka was selected as the study area because of its rapid urban expansion and diverse land characteristics.

The region contains:

* Dense urban settlements
* Agricultural land
* Vegetation areas
* Rivers and water bodies
* Bare land

The diversity of land surfaces makes Dhaka an appropriate location for evaluating satellite-based land cover classification methods.

---


Project Workflow
----------------------
The complete workflow follows a remote sensing and data-driven analysis pipeline:

```
Satellite Image Collection
            |
            ↓
Landsat 8 Time-Series Data
            |
            ↓
Image Filtering & Pre-processing
            |
            ↓
Cloud Removal
            |
            ↓
NDVI Calculation
            |
            ↓
Feature Extraction
            |
            ↓
Land Cover Classification
            |
            ↓
Accuracy Evaluation
            |
            ↓
Land Cover Map Generation
```

---

Dataset
-------------------
Landsat 8 Satellite Imagery

This project uses **Landsat 8 multispectral satellite data**.

Selected Spectral Bands

| Band   | Description         | Purpose                         |
| ------ | ------------------- | ------------------------------- |
| Band 4 | Red                 | Vegetation absorption analysis  |
| Band 5 | Near Infrared (NIR) | Vegetation reflectance analysis |

The satellite images are processed using Google Earth Engine for efficient large-scale computation.

---

NDVI Analysis

The project uses the **Normalized Difference Vegetation Index (NDVI)** to measure vegetation density and health.

NDVI Formula

[
NDVI = \frac{NIR - RED}{NIR + RED}
]

Where:

* **NIR** = Near Infrared band
* **RED** = Red band

NDVI values represent the difference between vegetated and non-vegetated surfaces.

NDVI Interpretation

| NDVI Range | Interpretation                          |
| ---------- | --------------------------------------- |
| < 0        | Water bodies, clouds, snow              |
| 0 - 0.2    | Built-up areas and bare land            |
| 0.2 - 0.5  | Sparse vegetation and agricultural land |
| > 0.5      | Dense vegetation                        |

---

# Land Cover Classification

The project identifies major land cover categories based on satellite spectral information and NDVI characteristics.

 1. Water Bodies

Examples:

* Rivers
* Lakes
* Wetlands

Characteristics:

* Low or negative NDVI values

---

2. Built-up Areas

Examples:

* Buildings
* Roads
* Urban infrastructure

Characteristics:

* Low vegetation response
* Higher reflectance in visible bands

---

 3. Vegetation

Examples:

* Cropland
* Grassland
* Trees

Characteristics:

* Positive NDVI values

---

4. Dense Vegetation

Examples:

* Forest areas
* High vegetation coverage

Characteristics:

* High NDVI values

---

# Methodology

The project follows a data-driven remote sensing approach:

## 1. Satellite Data Acquisition

Satellite imagery is collected from the Landsat 8 archive through Google Earth Engine.

---

## 2. Image Pre-processing

The collected images are processed through:

* Cloud masking
* Image filtering
* Temporal compositing
* Spectral band extraction

---

## 3. NDVI Generation

NDVI values are calculated using Red and Near Infrared bands to identify vegetation intensity.

---

## 4. Classification

Training samples are collected from satellite imagery and used for land cover classification.

Classification approaches include:

* Maximum Likelihood Classification
* Random Forest
* CART
* Support Vector Machine (SVM)

---

## 5. Result Visualization

The final outputs include:

* NDVI visualization maps
* Classified land cover maps
* Spatial distribution analysis
* Area statistics

---

# Google Earth Engine Implementation

Google Earth Engine provides the computational environment for this project.

Advantages of using GEE:

* Access to large satellite image collections.
* Cloud-based geospatial processing.
* No requirement for local satellite data storage.
* Efficient processing of multi-temporal imagery.
* Interactive map visualization.

---

# Technologies Used

| Technology          | Usage                              |
| ------------------- | ---------------------------------- |
| Google Earth Engine | Satellite image processing         |
| JavaScript API      | GEE workflow development           |
| Landsat 8           | Remote sensing dataset             |
| NDVI                | Vegetation analysis                |
| GIS                 | Spatial analysis and visualization |
| Machine Learning    | Land cover classification          |

---

# Project Outputs

## NDVI Map

A vegetation index map showing vegetation intensity across the study region.

Example interpretation:

* Green → High vegetation
* Yellow → Moderate vegetation
* Red → Low vegetation
* Blue → Water

---

## Land Cover Classification Map

Generated thematic maps representing:

| Class            | Visualization |
| ---------------- | ------------- |
| Water            | Blue          |
| Dense Vegetation | Dark Green    |
| Vegetation       | Light Green   |
| Built-up Area    | Red           |
| Bare Land        | Yellow        |

---

## Statistical Analysis

The system can calculate:

* Percentage of land coverage
* Area occupied by each class
* Seasonal vegetation changes
* Spatial distribution of land types

---


Applications
------------------

This project can support:

## Environmental Monitoring

* Vegetation health monitoring
* Ecosystem assessment
* Land degradation analysis

## Urban Planning

* Urban expansion analysis
* Land-use change detection

## Agriculture

* Crop monitoring
* Agricultural land assessment

## Climate Research

* Surface change analysis
* Environmental impact studies

---

# Advantages

* Uses freely available satellite imagery.
* Provides scalable cloud-based processing.
* Reduces manual land cover mapping effort.
* Supports reproducible remote sensing workflows.
* Suitable for environmental and urban analysis.

---

# Limitations

* Landsat spatial resolution may not capture very small objects.
* NDVI mainly represents vegetation information.
* Classification accuracy depends on training data quality.
* Seasonal variation can influence spectral responses.

---

# Future Improvements

Future development can include:

* Integration of Sentinel-2 higher-resolution imagery.
* Multi-index analysis using:

  * NDWI (Water Index)
  * NDBI (Built-up Index)
  * EVI (Enhanced Vegetation Index)
* Advanced machine learning models.
* Deep learning-based segmentation.
* Automated land cover change detection.
* Web-based interactive GIS dashboard.

---

Research Background
-------------------------

This project is based on the research work:

**"Land Cover Classification based on NDVI using LANDSAT8 Time Series Dataset: A Case Study of Dhaka Region, Bangladesh"**

The research demonstrates the effectiveness of Landsat 8 time-series imagery, NDVI analysis, and supervised classification techniques for identifying land cover patterns in the Dhaka region.

---

# Related Works & References

## 1. Rana, S. (2023)


**Land Cover Classification based on NDVI using LANDSAT8 Time Series Dataset: A Case Study of Dhaka Region, Bangladesh**

Contribution:

* Landsat 8 based land cover analysis
* NDVI-based classification
* Dhaka region case study

---



## 2. Tucker, C. J. (1979)

**Red and Photographic Infrared Linear Combinations for Monitoring Vegetation**

Contribution:

* Introduced NDVI methodology
* Established vegetation monitoring using satellite data

---

## 3. Gorelick, N., Hancher, M., Dixon, M., et al. (2017)

**Google Earth Engine: Planetary-scale Geospatial Analysis for Everyone**

Contribution:

* Introduced Google Earth Engine
* Enabled cloud-based satellite image analysis

---

## 4. Hansen, M. C., Potapov, P. V., Moore, R., et al. (2013)


**High-Resolution Global Maps of 21st-Century Forest Cover Change**

Contribution:

* Demonstrated Landsat-based land monitoring
* Supported large-scale land cover analysis

---

## 5. Breiman, L. (2001)

**Random Forests**

Contribution:

* Introduced Random Forest machine learning algorithm
* Widely applied in remote sensing classification

---

## 6. Mountrakis, G., Im, J., & Ogole, C. (2011)

**Support Vector Machines in Remote Sensing: A Review**

Contribution:

* Reviewed machine learning approaches for satellite image classification

---


Author
------------------
**Sohel Rana**

Digital Currency Investor & Technical Lead

GitHub; https://github.com/SohelRana-aiub-Pro/Data-Driven-Land-Cover-Classification-using-NDVI-GEE-Platform

# Keywords

```
Earth observations/Remote Sensing
Google Earth Engine
NDVI
Landsat 8
Land Cover Classification
GIS/Geo AI
Satellite Image Processing
Machine Learning
Environmental Monitoring
```

# Conclusion

This project demonstrates the application of **remote sensing, GIS, NDVI analysis, and data-driven classification techniques** for automated land cover mapping.

By combining satellite observations with cloud-based geospatial computing, this workflow provides an efficient solution for monitoring environmental and urban changes at regional scales.



Related Resourcses; https://www.irjet.net/archives/V7/i3/IRJET-V7I3577.pdf


https://www.nrsc.gov.in/nrscnew/assets/pdf/ebooks/Chap_2_LULC.pdf


https://www.mdpi.com/2072-4292/14/21/5455
