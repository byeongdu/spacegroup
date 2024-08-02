# Overview
This is a software package for Small Angle Scattering (SAXS or SANS) from self-assemblies. Building blocks can be geometric objects (such as nanoparticles), atomic coordinates (such as proteins), or voxel models. There are several GUIs for different jobs. 
## Indexing
This program is to index SAXS powder diffraction patterns in q space. 
## Spacegroup
This program is to simulate diffraction pattern from nanoscale assembly. It can build a crystal model with various polyhedra. Once a model is ready, either 2D or 1D SAXS pattern can be calculated. Currently, only 1D powder diffraction may be open to use.
## drawccp4
This program is to visualize the CCP4 format volumetric data. It will be ideal if the data is generated by superflip and its inflip file is available.
# Requirement
This is a program written in matlab, requiring to have a matlab license.
No additional matlab toolbox is needed.

# Installation
Clone the package with git, or download codes from the 'code' pulldown menu, for example as a zip. 

# How to start
1. Define the source, data, and download folders as your matlab path. If not familiar with this, take a look at the direction from Mathworks. [https://www.mathworks.com/help/matlab/matlab_env/add-remove-or-reorder-folders-on-the-search-path.html#:~:text=Change%20Folders%20on%20Search%20Path%20Interactively,-Use%20the%20Set&text=On%20the%20Home%20tab%2C%20in,folders%20to%20MATLAB%20search%20path.]

2. To run spacegroup, on matlab prompt >> spacegroup. 
3. You can load 'structure' and 'particle' model from the menu.
4. To run indexing software, type indexing on matlab prompt.

# Example
Data included in 'example' has been published in Nature Materials 21, 580-587 (2022)[https://www.nature.com/articles/s41563-021-01170-5]

# Credits
All downloaded matlab codes are available in the download folder along with each licence disclaimer. 
The crystallographic space group is based on syminfo.lib from CCP4 and ccp4 space group c-codes[https://github.com/dials/ccp4io/tree/master/libccp4/ccp4] are translated into matlab by me. Use this at our own risk. Files whose names start with 'GSAS_' are translated from python codes available from GSAS website. [https://gsas-ii.readthedocs.io/en/latest/index.html]
