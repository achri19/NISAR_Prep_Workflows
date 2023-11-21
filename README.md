# NISAR_Prep_Workflows

This repo contains notebooks for preparing for the NISAR Ecosystems ATBD notebooks: https://gitlab.com/nisar-science-algorithms/ecosystems/atbd


## Ecosystems_InputPrep_UAVSAR.ipynb
This notebooks downloads NISAR-simulated UAVSAR data

## Ecosystems_InputPrep_Sentinel1_SNAP.ipynb
This notebook queries and downlods Sentinel-1 from ASF and processes uses SNAPPY

## Ecosystems_InputPrep_ALOS2-NISAR.ipynb
This notebook runs downloads ALOS2 SLC data (access restricted), converts to NISAR RSLC and NISAR GCOV using ISCE3

*Requires the gcov.yaml file

## Ecosystems_InputPrep_NISAR.ipynb
This notebook extracts HH and HV from NISAR GCOV H5 data files, crops to desired area, aligns to the first reference image, and saves as GeoTiffs, and 
