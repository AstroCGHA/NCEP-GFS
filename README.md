# NCEP FNL-GFS Data Analysis and Visualization Notebooks

Visualizing NCEP/GDAS' FNL Meteorological Dataset, core of GFS Model, 
at 0.25 x 0.25 degree. These dataset can be queried via NCAR/UCAR RDA (https://rda.ucar.edu/) or
direct to THREDDS Server (https://thredds.ucar.edu/thredds/catalog/catalog.html).

These notebooks that I created are used for my bachelor's thesis. However, it 
can be used, accordingly based on your preference i.e. location, time, etc. Thus, you can definitely
make improvements out of it.

These notebooks include synoptic and mesoscale (e.g. convective and kinematic) parameters.

I've used Python ver. 3.9.x and the python packages mostly used in these notebooks are Cartopy, Matplotlib, MetPy (both 1.3 on Desktop and 1.5 on Laptop), NumPy, and Xarray. Make sure you have those!

---------------
As of July 17, 2023

Major Tweak(s):
1. Revised the notebook for SRH incorporating and visualizing RM and LM components using Bunkers Internal Dynamics (ID) Method.

As of July 6, 2023

Major Tweak(s):
1. Added a notebook for 0-3 km Streamwise Helicity and 0-500 m Streamwise Vorticity.

Minor Tweak(s):
1. Changes to plot titles in STM and SRH notebook.

As of June 30, 2023

Major Tweak(s):
1. Changes to Storm-relative (SR) Motion and SR Helicity ntbk. Computed for user-defined SRH and averaged
with the NCEP FNL's SRH product. Also includes 0-1 km SRH. Used a different colormap.

As of April 6, 2023

Major Tweak(s):
1. Changes to the notebook involving Mean Precipitation. New custom cmaps at various rates.
2. Adjusted gaussian smoothing to most of the NCEP FNL notebooks.
3. Provided a quick fix to the surface U-wind component in the Dewpoint chart. 

Minor Tweak(s):
1. Subtle changes to plot titles involving symbols instead of proxy abbreviations. 
2. Reversed the color scheme in Atmospheric Thickness to accomodate temperature variation.
