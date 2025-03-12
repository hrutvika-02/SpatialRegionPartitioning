# SpatialRegionPartitioning
# Cardinality-Based Spatial Partitioning

This repository contains two Jupyter notebooks implementing the Spatial Partitioning algorithm (PRRP) and its improved version (PRRP-I). Both algorithms aim to partition spatial datasets efficiently while considering cardinality constraints. The shapefile used for experimentation is also included in the repository.

## PRRP 
The PRRP_version.ipynb file implements the P-Regionalization through Recursive Partitioning algorithm (PRRP). You can run this notebook to explore the algorithm's implementation and results on the provided dataset.

## PRRP-I 
The PRRP-I_version.ipynb file implements the improved version of the algorithm (PRRP-I). It modifies the PRRP algorithm by introducing cardinality constraints for each region. Run this notebook to compare the performance of the improved algorithm with the original.

## Repository Structure

The repository consists of the following files and directories:

- `PRRP_version.ipynb`: A Jupyter notebook implementing the Cardinality-Based Spatial Partitioning algorithm (PRRP).
- `PRRP-I_version.ipynb`: A Jupyter notebook implementing the improved version of the algorithm (PRRP-I), which incorporates cardinality constraints for each region.
- `cb_2015_42_tract_500k.shp`: The shapefile used for spatial partitioning experiments.
- `cb_2015_42_tract_500k.shx`: The index file for the shapefile.
- `requirements.txt`: A file listing the required Python libraries and dependencies.

## Prerequisites

Before running the notebooks, ensure you have the following software installed:

- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)

To install the required dependencies, run:

```bash
pip install -r requirements.txt
