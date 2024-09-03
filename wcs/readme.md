# Learning Journey for the Processing of Water Column Sonar Data

## Overview
Water column sonar data, the acoustic back-scatter from the near-surface to the seafloor, are used to assess physical and biological characteristics of the ocean including the spatial distribution of plankton, fish, methane seeps, and underwater oil plumes. There are a variety of sonar systems including single and multibeam echosounders using single frequency, multiple frequencies, or wideband technology.
     
These systems deliver valuable information for ecosystem-based fisheries management but they also produce large data volumes that are costly and complicated to maintain. In collaboration with NOAA Fisheries and CIRES, NCEI archives water columnn sonar data collected from NOAA, academic, and internationals fleets. Archived data are globally accessible through the archive's [data portal](https://www.ncei.noaa.gov/maps/water-column-sonar/) as well as on Amazon Web Services through the NOAA Open Data Dissemintation Project ([NODD](https://www.noaa.gov/information-technology/open-data-dissemination)).

The native sonar data are large, complex, and recorded in instrument-specific binary file formats. Embedded in the native file's metadata and datagrams are a number of fields including sonar configuration information, navigation information, calibration coefficients and power data from single or multiple sonar frequencies. File names contain the start time for that file, and often include a preceding tag for that cruise or deployment. The timestamp in UTC follows the convention: ‘D’YYYYMMDD’-T’hhmmss. For example, “SaKe2015-D20150719-T193412”, indicates a files from a 2015 SaKe cruise and the start of the file is July 19, 2013 at 19:34:12 (UTC).
    
The largest volume of raw sonar data in the [NCEI archive](https://www.ncei.noaa.gov/products/water-column-sonar-data) were collected using Simrad EK60 (18-710 kHz, split beam) and EK80 (18-710 kHz, split beam and broadband) echosounders.

This tutorial demonstrates EK60 data processing in the cloud using [echopype](https://echopype.readthedocs.io/en/stable/), an open-source, python-based module for reading, processing, and visualizing water-column echosounder files developed by scientists at the University of Washington.

## In this Learning Journey there are four python notebooks:

1. Echopype EK60 Cloud Processing
   - By working through this notebook, you will learn how to:
     - install echopype
     - read a raw EK60 file from an Open Data S3 bucket
     - find the calibrated volume backscattering strength (Sv)
     - plot data

3. Frequency Differencing with L2 EK60 Data
   - By working through this notebook, you will learn how to:
     -access data from an S3 bucket
     - read an EK60 file
     - use Xarray to read cloud-native Zarr formatted files
     - apply frequency differencing to analyze the data
     - plot results

4. Geospatial Indexing
   - By working through this notebook, you will learn how to:
     - access data from an S3 bucket
     - use Xarray to read cloud-native Zarr formatted files
     - extract navigation data from a Zarr store
     - use GeoPandas to organize geospatial data into GeoJSON format
     - plot geospatial data in a mapping interface

5. Segmenting Echosounder Data
   - By working through this notebook you will learn how to:
     - Install SAM
     - Download and transform the data
     - Load a trained model
     - Generate a mask of the data
