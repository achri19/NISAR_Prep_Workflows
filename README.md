# NISAR_Prep_Workflows

This repo contains notebooks for preparing for the NISAR Ecosystems ATBD notebooks: https://gitlab.com/nisar-science-algorithms/ecosystems/atbd

# Conversions
## Conversions_ALOS2-SLC_to_NISAR-GCOV.ipynb
This notebook runs downloads ALOS2 SLC data (access restricted), converts to NISAR RSLC and NISAR GCOV using ISCE3

## Conversions_ALOS1-L1.0_to_NISAR-GCOV.ipynb
This notebook runs downloads ALOS1 L1.0 data (queried from ASF DAAC), converts to NISAR L0B, NISAR RSLC, and NISAR GCOV using ISCE3

# Prepare Input Files
## Ecosystems_InputPrep_NISAR.ipynb
This notebook extracts HH and HV from NISAR GCOV H5 data files, crops to desired area, aligns to the first reference image, and saves as GeoTiffs, and 

## Ecosystems_InputPrep_UAVSAR.ipynb
This notebooks downloads NISAR-simulated UAVSAR data

## Ecosystems_InputPrep_Sentinel1_SNAP.ipynb
This notebook queries and downlods Sentinel-1 from ASF and processes uses SNAPPY

