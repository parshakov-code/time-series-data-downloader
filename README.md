# Time Series Data Downloader & Preprocessor
Time-Series Data Downloader & Preprocessor (TSDP) is an open-source Python tool for automating the download and preprocessing of Landsat 1–9 (including MSS and panchromatic), Sentinel-2, GEDI, and other satellite datasets from Google Earth Engine, Copernicus, and NASA Earthdata, for user-selected MGRS tiles. TSDP preserves the original spectral and spatial resolutions of all products.

TSDP integrates modern preprocessing algorithms—including Cloud Score+ for Sentinel-2 cloud detection, SCS+C topographic illumination correction, wildfire-smoke masking, MSS-to-TM co-registration, and other routines—helping researchers produce high-quality datasets ready for multi-resolution time-series analysis (e.g., UC-Change), an emerging class of techniques that can fully utilize the unique information provided by each sensor.

---

## Usage
- Open "Time_Series_Data_Downloader.ipynb" as a Jupyter Notebook in any Python code editor.
- Configure the MGRS tile, sensors, preprocessing and download parameters.  
- Run the notebook to automatically download and preprocess satellite imagery.  

TSDP is provided as a single Jupyter Notebook and installs all required libraries automatically. The notebook includes detailed explanations of all parameters and workflow steps, with further discussion available in the technical note referenced below.

---

## Citation
If you use **TSDP** in your research, please cite:
**Parshakov, I., & Chen, D. (2026). TSDP: Automatic preprocessing and downloading of Landsat 1–9, Sentinel-2, and other remote sensing data for multi-resolution time-series image analysis. Big Earth Data, 1–33. https://doi.org/10.1080/20964471.2026.2663576**
