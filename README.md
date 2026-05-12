# Comparing Satellite-Based Remote Sensing Tools for Measuring Forest-Fire Recovery in California
**Ashley Torres** | NYU Department of Environmental Studies | Honors Thesis 2026
Advised by Dr. Yi Yin & Dr. Sonali McDermid

## Overview
This repository contains the analysis code for my undergraduate honors thesis examining
post-fire recovery trajectories in California forests using MODIS-derived NDVI and
Solar-Induced Fluorescence (SIF) from 2001-2023.

## Data
Raw satellite data are publicly available (see sources below) and were preprocessed
into .npy arrays prior to analysis. Preprocessed arrays are not included due to file
size constraints. Preprocessing code is available upon request.

## Data Sources
- Burned Area: MODIS MCD64A1 - NASA LP DAAC
- Land Cover: MODIS MCD12Q1 - NASA LP DAAC
- Fire Radiative Power: MODIS MOD14A1/MYD14A1 - NASA LP DAAC
- NDVI: MODIS MOD13Q1 - NASA LP DAAC
- SIF: GOSIF - University of New Hampshire (Li & Xiao, 2019)
- Fire Perimeters: CAL FIRE FRAP database

## Requirements
pip install -r requirements.txt
