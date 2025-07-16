# las_to_geotiff
This repository presents a simple pipeline that processes LiDAR or photogrammetry point clouds into a georeferenced Digital Elevation Model (DEM) using the PDAL and GDAL libraries.



## Setting up the Environment

We use **Pixi** as a package manager in this project. After cloning this repository, make sure you have the `pixi.toml` file and install Pixi. The installation steps are explained in the official [Pixi documentation](https://pixi.sh/latest/installation/).

After installing Pixi, you can set up the environment by running:

```bash
pixi install
```

Then start the Pixi environment with:

```bash
pixi shell
```
The goal is to start from a LAS/LAZ point cloud and generate various GeoTIFF files, from a DEM to hillshade. To achieve this, we will follow the step-by-step tutorial below.

# Download Open Source Point Cloud Data

For this project, we need LiDAR and photogrammetry point clouds. We will use [OpenTopography](https://opentopography.org/), which is an open platform that provides free and publicly available high-resolution topographic data.

This video explains how to download an example point cloud that can be used in this project.

The `example_data` folder contains an input file downloaded from OpenTopography, as well as output files generated using this project.
