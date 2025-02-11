# Site Suitability Analysis for Hospital Locations

## Overview
This repository contains a site suitability analysis for hospital locations using raster data and weighted overlay techniques. The analysis integrates spatial datasets such as population density, hospital proximity, road accessibility, land use, and slope to determine the best locations for new hospitals.

## Objectives
- Identify the most suitable locations for hospitals using GIS-based analysis.
- Process raster datasets exported from ArcGIS Pro.
- Apply weighted overlay methods to compute suitability scores.

## Methodology
The analysis follows a structured GIS-based approach:

### Step 1: Prepare the Data
- Load raster datasets related to suitability factors.
- Use Python libraries such as `rasterio`, `numpy`, and `pandas` for data handling.

### Step 2: Define Weighted Overlay Function
- Create a function that computes a suitability index based on weighted criteria.

### Step 3: Compute Suitability Scores
- Combine multiple raster datasets using weighted overlay analysis.
- Normalize and rescale values to ensure comparability.

### Step 4: Visualize Results
- Generate spatial maps using `matplotlib`.
- Overlay results on geographical maps.

## Requirements
Ensure the following Python libraries are installed before running the analysis:
```bash
pip install rasterio numpy pandas matplotlib
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/bnvaidya20/site-suitability-analysis.git
```
2. Navigate to the project directory:
```bash
cd site-suitability-analysis
```
3. Run the Jupyter Notebook:
```bash
jupyter notebook site_suitability_analysis.ipynb
```

## Dataset Description
The analysis considers the following spatial datasets:
- **Population Density**: Areas with higher populations are prioritized.
- **Hospital Proximity**: Accessibility to existing hospitals is factored in.
- **Road Proximity**: Connectivity to major roads is evaluated.
- **Land Use**: Suitable land types for hospital construction.
- **Slope**: Flat terrain is preferred for construction feasibility.

## Results
- A final suitability map highlights the best locations for hospitals.
- The results can be used for urban planning and healthcare accessibility studies.

## License
This project is licensed under the MIT License.

## Contact
For inquiries, reach out at [bnvaidya](bnvaidya@mail.com).