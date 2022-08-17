# Mangrove Canopy Height from SRTM Data and User-Selected Mangrove Extent
These scripts apply the method developed by Simard et al., 2019 (https://doi.org/10.1038/s41561-018-0279-1) to calculate mangrove canopy height from SRTM data. The scripts can be modified by the user to designate a specific region of interest and a mangrove spatial extent layer.  

They should be run in the following order:
1.  srtm_download.py
2.  srtm_mangrovehgt.py
3.  srtm_mangrovemask.py
4.  srtm_mangrove_polygons.py

This work was funded by the InterAmerican Development Bank (IDB).

The application of these scripts to mangrove canopies on Andros Island, The Bahamas is described in the following reports:
- [Pilot Project Report](https://drive.google.com/file/d/11q1gByhq9gwdNUD0GU-mQwlVlwLwoIqF/view?usp=sharing) - Mangrove delineation and canopy height analysis for Andros Island
- Pages 13-23 of [Demonstrating Technologies Report](https://drive.google.com/file/d/1WVyL14T7TNNNhNUOR4ytU9aHY_EaMoSa/view?usp=sharing)
- Chapter III: Detecting and mapping spatial variation in mangrove canopy height and extent in [Technical Note](https://drive.google.com/file/d/1oTcYz6Yv8VwTcl7irel971X_Q-_10oMM/view?usp=sharing)
