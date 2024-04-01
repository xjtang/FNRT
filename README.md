# FNRT
 Fusion Near Real Time (Operational)
 - 
 
 This is the operational version of the FNRT (Fusion Near Real Time) algorithm. 
 It is an algorithm for near real-time monitoring of tropical forest disturbance using time series analysis of Landsat, Sentinel-2, and Sentinel-1 data.
 The operational version streamlined the workflow and improved the scalability of the algorithm for operational monitoring over large areas.
 It also allows for pausing and resuming the monitoring, meaning the algorithm can monitor up to a certain time, pause and save the cache data, and then resume monitoring later when more data becomes available. 
 
 The original developer version can be found here: https://github.com/xjtang/fnrt-dev

 The publication of the algorithm can be found here: https://www.sciencedirect.com/science/article/abs/pii/S0034425723001773
 
 To run FNRT:
 - 
 
 - Clone the repository to Google Earth Engine
 - Fix the path of all the imports (change the user name to your own username)
 - Create a new folder in GEE Asset to save the results; within the folder, create three image collections (training/cache/alerts)
 - Configure your run in the parameters script (located under utilities)
 - Run training using run/training
 - Run monitoring using run/monitoring
 - Run filtering using run/filtering
 - Use dev/plotter to visualize the results

 Feel free to contact tang3xx@jmu.edu if you have any questions. 
 
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10903541.svg)](https://doi.org/10.5281/zenodo.10903541)
