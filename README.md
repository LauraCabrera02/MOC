This repository contains a Python notebook for calculating the Meridional Overturning Circulation (MOC) using a box model framework. The workflow involves reading ocean transport data from NetCDF files, integrating it zonally, and visualizing the MOC streamfunction. 📑 Contents

The notebook MOC_boxmodel.ipynb covers the following steps:

📦 Reading NetCDF files using xarray

⚙️ Extracting meridional transport and grid information

🔍 Computing the overturning streamfunction by zonal integration

🌍 Plotting the MOC using Matplotlib and Cartopy

📊 Data

The notebook works with transport data in NetCDF format, specifically:

ty_transport: meridional volume transport integrated over depth

A corresponding grid file defining the model domain and latitude/depth dimensions

📌 Note: Data files should be placed in the same directory as the notebook or the file paths adjusted accordingly.

🛠️ Requirements

To run this notebook, the following Python libraries are required:

xarray

numpy

matplotlib

cartopy

netCDF4

