# GRIB2 File Processor

This Jupyter Notebook processes GRIB2 files by downloading them from Climate Change Canada’s Regional Air Quality Deterministic Prediction System (RAQDPS). It extracts latitude, longitude, and PM2.5 concentration data, and saves the results to a CSV file.

## Features
- Downloads GRIB2 files from Climate Change Canada’s RAQDPS.
- Extract latitudes, longitudes, and PM2.5 concentration data from the GRIB2 file.
- Save the extracted data to a CSV file.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - `pygrib`
  - `requests`
  - `pandas`

To install the required libraries, you can run:

```bash
pip install pygrib requests pandas
```
