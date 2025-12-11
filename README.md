# Colorectal-cancer-dataset-MIR-spectroscopy-and-WSIs-

This is a small supplementary repository to support the handling of the Multimodal colorectal cancer dataset (FT-IR spectroscopy and Whole Slide Imaging) available on Zenodo under DOI: [10.5281/zenodo.17790337](https://doi.org/10.5281/zenodo.17790337).

```bash 
training
├── CRC_data_showcase.ipynb
├── CRC_metadata_val.ipynb
├── MIR_technval.ipynb
├── WSI_technval.ipynb
├── MIR_fsm_to_txt.ipynb
```

- MIR_fsm_to_txt.ipynb: a function that uses the specio Python package to load .fsm files and then converts them into .txt tables and generates the spatial positions of the mid-infrared spectra, while also saving the spectral metadata to a .json file.
- CRC_data_showcase.ipynb: an example notebook for looking at the different data types in the database.
- CRC_metadata_val.ipynb: a notebook containing some basic analysis on the main metadata files.
- WSI_technval.ipynb: the technical validation workflow of the Whole Slide Images using OpenSlide Python complete with tissue core-wise sharpness computation and circle detection.
- MIR_technval.ipynb: the technical validation workflow of the mid-infrared spectroscopy dataset and some data analysis tools: conversion from transmittance to absorbance, filtering out background spectra, signal-to-noise ratio distributions, the presence of atmospheric effects, and baseline drift.
