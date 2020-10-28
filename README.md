# semantic_map

## Description

Creation of a semantic map (2D projection) from 3D PCL and Mask

## Dependancies

yolact_ros
apt packages : 
ros_numpy
tf2_ros
numpy
itertools

#Installation and running

catkin_make
source devel/setup.bash

## Debug

It will be slow for sure


## TODO

Main Workflow

- [] Get PointCloud from 3D camera
- [] Get Mask from Yolact
- [] Associate each Mask with the corresponding PCL
- [] Convert PCL into the map frame
- [] Project the PCL on 2D (ground)
- [] Creation of a temp map with all info from the PCL & Mask
- [] Add this map to the main map

Improvements & Debug 

TBD