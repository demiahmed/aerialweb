# AerialWeb Satellite Imagery Explorer

Hello, this project is the face of my Master's thesis on Exploring Sentinel2's Open Access Satellite Imagery on a Python based workflow that procedurally collects large pieces of images based on Area of Interest marked using boundary coordinates and extents. The images are retrieved using the Sentinel API part of Copernicus mission by the European Space Agency (ESA).

Feel free to clone this repository and add/modify and even request merges to make the code better as its an early stage work in development.

## Functions

1. Query based service for retrieving satellite images in order (sorted by Passenger Traffic numbers) in batches for performance optimisation (**DownloadScript.ipynb**)
2. Quert based service for retrieving satellite images based on country's airports. (**CountryScript.ipynb**)
3. Horizontal Image Query of the same location on different dates and export as **GIF** or **Video** (**GIFmaker.ipynb**)

## Pre-requisites

Make sure that you have configured the conda environment using the `aerialweb.yml` file and installed all the dependencies. There may be a few dependencies such as `fiona` and `GDAL` producing compatibility issues in Mac OSX which needs to be worked on. Reach out to me if you happen to face such issues :)

