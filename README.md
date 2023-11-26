# Analyzing-burn-severity


## Overview

This repository contains a Python script for analyzing burn severity using Google Earth Engine and geemap. The script calculates the normalized burn ratio (NBR) and the difference normalized burn ratio (dNBR) to assess burn severity after a fire event.

## Requirements
- geemap
- Earth Engine Python API

## Usage

1. Install the required Python packages:

```bash
pip install geemap earthengine-api
Open the Jupyter Notebook or Python script and run the provided code.

Customize the script according to your study area, date range, and other parameters.

View the results on the map and export the burn severity layer.

###Script Components
Script File: [burn_severity_analysis.py](https://colab.research.google.com/drive/1p4fZebG4YU8CBBNzvIGgEHXI0JBfGfsC?usp=sharing)
Functions:
mask_s2_clouds: Masks clouds in Sentinel-2 data.
calculate_and_export_dNBR: Calculates and exports dNBR for pre- and post-fire periods.
Visualization:
Displays dNBR and burn severity index on the map.
Exports the burn severity layer to Google Drive.


###Acknowledgements
Google Earth Engine
geemap
OpenAI GPT-3

###Author
Lucas Vituri Santarosa

Contributing
Contributions are welcome! Please create an issue or submit a pull request.
