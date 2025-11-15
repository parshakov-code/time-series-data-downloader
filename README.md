# Time Series Data Downloader
Time-Series Data Downloader (TSD) is an open-source Python tool for automating the download and preprocessing of Landsat 1–9 (including MSS and panchromatic), Sentinel-2, GEDI, and other satellite datasets from Google Earth Engine, Copernicus, and NASA Earthdata, for user-selected MGRS tiles. TSD preserves the original spectral and spatial resolutions of all products.

TSD integrates modern preprocessing algorithms—including Cloud Score+ for Sentinel-2 cloud detection, SCS+C topographic illumination correction, wildfire-smoke masking, MSS-to-TM co-registration, and other routines—helping researchers produce high-quality datasets ready for multi-resolution time-series analysis (e.g., UC-Change), an emerging class of techniques that can fully utilize the unique information provided by each sensor.

---

## Usage
- Open "Time_Series_Data_Downloader.ipynb" in Jupyter Notebook.  
- Configure the MGRS tile, sensors, and download parameters.  
- Run the notebook to automatically download and preprocess satellite imagery.  

TSD is provided as a single Jupyter Notebook and installs all required packages automatically. The notebook includes detailed explanations of all parameters and workflow steps, with further discussion available in the technical note referenced below.

---

## Citation
If you use **TSD** in your research, please cite:
**Parshakov, I., & Chen, D., 2025. Time Series Data Downloader: automatic preprocessing and downloading of Landsat 1–9, Sentinel-2, and other remote sensing data for multi-resolution time-series image analysis. Submitted to *Big Earth Data*.**
