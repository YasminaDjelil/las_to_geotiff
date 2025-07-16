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
