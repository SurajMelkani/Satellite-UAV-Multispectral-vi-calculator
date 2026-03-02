# Satellite & UAV Multispectral Vegetation Index Calculator

An interactive, web-based tool built with **Python** and **Streamlit** to rapidly process and visualize multispectral imagery (Red, Green, NIR, Red Edge, Blue) and RGB photos from satellite and drone platforms.

## Overview
This application allows users to upload single-band GeoTIFFs to dynamically compute up to 11 distinct vegetation indices. It processes the imagery at a preview resolution for rapid rendering and requires no Coordinate Reference System (CRS) transformations, making it highly efficient for quick field assessments.

**Supported Indices:**
* **NDVI, GNDVI, NDRE, SAVI** (Standard & Soil-Adjusted)
* **EVI, EVI2** (Enhanced Vegetation Indices for high biomass)
* **NGRDI, RENDVI, NIRRENDVI** (Red-Edge and Visible contrast)
* **RGBVI, VARI** (RGB-only indices)

