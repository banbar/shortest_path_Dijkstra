# Introduction

Shortest Path Problem (SPP) is one of the common use-cases in spatial analysis. From finding a route to resource management, it has a wide application domain. This repository aims to improve the process of learning SPP by utilising open-source software, including the *[NetworkX](https://networkx.org/)* and *[GeoPandas](https://geopandas.org/en/stable/)* packages of Python. The experiments are carried out on the openly available road network dataset of *[San Francisco](https://drive.google.com/file/d/0B9mshE5t1uUCNVEyb1Q2dkQzc2c/view?resourcekey=0-X-WGa3oP1Cu1VYct0fCmYw)*. A Jupyter Notebook is created to facilitate the computational reproducibility of this repo. QGIS is used to visualise the dataset.

# Data Preprocess

## Converting CSV Files into a SHP file

The downloaded data is in the CSV format, which makes it difficult to visualise it on QGIS.
