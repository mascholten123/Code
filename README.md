This Folder contains the Python scripts for the masters thesis project titled "Designing a methodology for optimized small-scale solar-drip irrigation systems in the Dominican Republic" conducted by Mirabelle Amelia Scholten. 

The file organization is as follows: 
- NetworkCode -- Contains all scripts regarding the irrigation network
    - DripNetwork.ipynb: models the H vs. Q characteristics of a drip irrigation network 
    - EconomicGraphs.ipynb: Creates NPC and intial investment cost graphs for report based on result founds using google sheets calculations
    - PlantWaterCalcs.ipynb: Determine irrigation needs based on historical weather data 
    - SensitivityAnalysis.ipynb: find sizing alternatives for direct drive, battery and tank configurations accounting for possible climate change effects for the year 2050 

- pumpCode -- Contains scripts to determine the pump curve from manufactors data sheet

- SolarCode -- Contains scripts for SDIS system sizing for 1, 2 and 3 ha scenerios

- TrackingCode -- Contains script to compare tracking PV vs fixed in the Dominican Republic 