# Comprehensive Solar Energetic Electron event Catalogue (CoSEE-Cat) Data Release 1
This project is to extend the analysis in Figure 19d from Warmuth 2025 by finding flares for the 15 SEEs without STIX data. 

## Data
The CoSEE-Cat data release 1 was downloaded from https://coseecat.aip.de/metadata/coseecat_dr1/ on 12th November 2026. 

## Method
The aim is to identify the solar electron events in the catalogue that didn't have associated STIX flares. Use SolarMach to identify other observers that might have imaged the flare associated with the event. Identify the flares and determine their location in longitude. Calculate the difference in longitude between the magnetic footpoint of SolarOrbiter when the SEE in CoSEE-Cat was observed and the position of the associated flare. Plot a new version of Figure 19d that includes the extra SEEs without STIX flares.


## References
Warmuth, A., Schuller, F., Gómez-Herrero, R., Cernuda, I., Carcaboso, F., Mason, G.M., Dresing, N., Pacheco, D., Rodríguez-García, L., Jarry, M. and Kretzschmar, M., 2025. CoSEE-Cat: A Comprehensive Solar Energetic Electron event Catalogue obtained from combined in situ and remote-sensing observations from Solar Orbiter: Catalogue description and first statistical results. Astronomy & Astrophysics, 701, p.A20.