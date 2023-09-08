This file encapsulates all of the notable changes of each notebook on this repository.

## As of Sept 8, 2023

Tweak(s):
1. Added a notebook for Barotropic and Baroclinic Potential Vorticity (PV) with Equivalent ThetaE.
2. Additional proper units and calculation of composite parameters without calling the magnitude function to make arrays dimensionless.
3. 
Note: Both notebooks containing Baroclinic and Barotropic PV with Equivalent ThetaE has pressure level limits to 500-hPa for visualization/analysis purposes in this case.

## As of July 20, 2023

Tweak(s):
1. Revised the notebook for SRH incorporating and visualizing RM and LM components using Bunkers Internal Dynamics (ID) Method.
2. Changed the method of calculating mean winds in the (1) Bunkers ID & SRH, (2) MSLP, Winds, BRN Shear, and (3) Updraft, EHI, SCP notebooks. Now using numpy with proper indexing.
3. Utilized smooth_n_point to various parameters i.e. evident in MSLP, Winds, BRN Shear notebook.
4. Added a BRN dimensionless parameter. Uncomment if need.
5. Proper units and calculation of composite parameters without calling the magnitude function to make arrays dimensionless.
6. Cleared extraneous some 'comments' in few notebooks.

## As of July 6, 2023

Tweak(s):
1. Added a notebook for 0-3 km Streamwise Helicity and 0-500 m Streamwise Vorticity.
2. Changes to plot titles in STM and SRH notebook.

## As of June 30, 2023

Tweak(s):
1. Changes to Storm-relative (SR) Motion and SR Helicity ntbk. Computed for user-defined SRH and averaged
with the NCEP FNL's SRH product. Also includes 0-1 km SRH. Used a different colormap from CMasher.

## As of April 6, 2023

Tweak(s):
1. Changes to the notebook involving Mean Precipitation. New custom cmaps at various rates.
2. Adjusted gaussian smoothing to most of the NCEP FNL notebooks.
3. Provided a quick fix to the surface U-wind component in the Dewpoint chart.
4. Subtle changes to plot titles involving symbols instead of proxy abbreviations.
5. Reversed the color scheme in Atmospheric Thickness to accomodate temperature variation.
