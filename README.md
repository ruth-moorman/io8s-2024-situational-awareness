# IO8S Cruise Plotting Tools

The notebooks in this repo use the [Copernicus Marine Toolbox python API](https://help.marine.copernicus.eu/en/articles/7970514-copernicus-marine-toolbox-installation) to download and plot SSH and SST satellite products subsetted for the region relevant to the IO8S 2024 cruise. These SSH and SST products also incluse some information on sea-ice coverage. SST for a given day (GMT) appears to be processed by day+2 and SSH by day +1.

Running these notebooks will require setting up a python environment with the following dependencies:
- [xarray](https://docs.xarray.dev/en/stable/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [cmocean](https://matplotlib.org/cmocean/)
- [Copernicus Marine Toolbox](https://help.marine.copernicus.eu/en/articles/7970514-copernicus-marine-toolbox-installation) 
