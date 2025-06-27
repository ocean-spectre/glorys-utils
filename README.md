# GLORYS Utils
Miscellaneous tools and scripts to interact with the [GLORYS dataset](https://data.marine.copernicus.eu/product/GLOBAL_MULTIYEAR_PHY_001_030/description).

## Getting started
Currently this is just a single jupyter notebook.

To get started, create a new conda environment with Python 3.11 and then `pip install -r requirements.txt`.

You may also need to run `pip install black[jupyter]` for formatting.

`pull_and_plot.ipynb` is a Jupyter notebook that pulls specified slices of the GLORYS dataset and plots the surface velocities at the first time step.

## Example
Example outputs have been included under `example`. Example data was pulled with the following parameters:

```python
dataset_id = "cmems_mod_glo_phy_my_0.083deg_P1D-m"
start_date = "2003-01-01"
end_date = "2003-01-01"
min_long = -90
max_long = 0
min_lat = 12
max_lat = 60
min_depth = 0
max_depth = 1
```