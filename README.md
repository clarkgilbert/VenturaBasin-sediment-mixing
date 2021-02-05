# VenturaBasin-sediment-mixing
Used to plot the figures in Gilbert_et_al_2021 which has been submitted for review in Geology.

author @clarkgilbert
This code was heavily modified by clarkgilbert from the CentralCA_ForwardMixing.py file within the 'sediment_unmixing' python package (https://github.com/grsharman/sediment_unmixing);(doi:10.1016/j.epsl.2017.07.044.).

This code was written to create the kernel density estimates in Figure 2 and the best fit mixture models in Figure 3 in the manuscript Gilbert et al. (2021) which was submitted to Geology for review. The sediment_unmixing package must be downloaded in order to use this script. The zircon geochronology data used in the manuscript can be found in the file named 'Table_A2_ZirconGeochronologyData.xlsx' within the data supplement of this manuscript. The 'VenturaBasinMixing.ipynb' must be moved into the 'sediment_unmixing-master' folder and the 'Table_A2_ZirconGeochronologyData.xlsx' file must be moved into the folder named 'Test Data' in order to work properly. Any questions can be directed to the corresponding author at clarkgilbert@mines.edu.

Dependencies

numpy 
matplotlib 
os

MixtureModel 
populationMetrics 
detritalPopulation
