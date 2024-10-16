# `Dask`-`xarray` Tutorial for Climate Science & Big-Data Analysis

This is an Interactive Tutorial designed as part of a workshop in [ETH Zurich UP](https://up.ethz.ch) focussed on `dask`-powered `xarray` for high-resolution climate, weather, & ocean/atmosphere model outputs. 
Projects such as [EERIE](https://eerie-project.eu) as well as sub-2.5 kilometre resolution coupled climate models such as the [ICON Model](https://www.icon-model.org) output from [EXCLAIM](https://exclaim.ethz.ch) have proven that efficient & effective use of `dask` is now increasingly necessary.
These scalable data analysis workflows are crucial to unlock the full potential of these rich datasets and advance our understanding of the Earth system.

## Tutorial Overview

1. **Notebook 0:** Fundamentals of task-based parallelism & `dask`, and creating/manipulating `dask`-backed `xarray` data.

2. **Notebook 1:** Avoiding common pitfalls, and grasping the science/art of chunking.

3. **Notebook 2:** Using the `Dask` Dashboard, design of task-based parallel algorithms, exploring advanced techniques & methods, and scaling up with `Dask` SLURM clusters.

## Getting Started

To run the notebooks, you'll need `python` installed along with the following libraries:
- `xarray`
- `numpy`
- `dask`
- `dask_jobqueue` (for Notebook 2)
- `flox` (for Notebook 2)

You can install the dependencies using pip:
```
pip install xarray numpy dask dask_jobqueue flox
```

## Dataset

The notebooks use example climate datasets resampled from a model run as part of the [EERIE Project](https://eerie-project.eu), now stored in `zarr` and `netCDF` format. Update the `data_dir` variable in each notebook to point to the location of your datasets.

