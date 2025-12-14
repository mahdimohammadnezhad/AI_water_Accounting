# ISIMIP Climate Data Downloader & ML-Water Accounting Framework

This repository provides a reproducible workflow for:
- Downloading ISIMIP3b climate forcing data
- Spatial subsetting using watershed shapefiles
- Preparing datasets for machine learning
- Training XGBoost models for climate impact analysis

## Requirements
- Python >= 3.8
- uv (recommended)

## Installation

```bash
git clone https://github.com/mahdimohammadnezhad/AI_water_Accounting.git
cd AI_water_Accounting

uv venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
uv pip install -r requirements.txt