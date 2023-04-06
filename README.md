# NCEP FNL-GFS Visualization Notebooks

Visualizing NCEP/GDAS' FNL Meteorological Dataset, core of GFS Model, 
at 0.25 x 0.25 degree. These dataset can be queried via NCAR/UCAR RDA (https://rda.ucar.edu/) or
direct to THREDDS Server (https://thredds.ucar.edu/thredds/catalog/catalog.html)

These notebooks that I created are used for my bachelor's thesis. However, it 
can be used, accordingly based on your preference i.e. location, time, etc. Thus, you can definitely
make improvements out of it.

I've used Python ver. 3.9.x with MetPy ver. 1.3. 

---------------
As of April 6, 2023

Major Tweak(s):
1. Changes to the notebook involving Mean Precipitation. New custom cmaps at various rates.
2. Adjusted gaussian smoothing to most of the NCEP FNL notebooks. 

Minor Tweak(s):
1. Subtle changes to plot titles involving symbols instead of proxy abbreviations. 
2.  Reversed the color scheme in Atmospheric Thickness to accomodate temperature variation.
