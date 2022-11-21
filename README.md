# Sudan-Electricity-sector-modelling
Description:
this repository contains datasets of inputs and outputs from three different energy models (OSeMOSYS, Calliope and Hypatia) used to explore pathways for the Sudaense electricity sector toward universal access of electricity by 2030 incorporating three different scenarios.

# Models versions:
the model was tested with the following Versions:
OSeMOSYS:
OSeMOSYS data were uploaded to the model using the interface developed by Eng. Mohammed Amin Tahavori available at:
https://github.com/mohammadamint/PYOF.git

OSeMOSYS python model available at: 
https://github.com/OSeMOSYS/OSeMOSYS_Pyomo/blob/master/osemosys.py

Calliope: 
Version 0.6.8. avilable at: 
https://calliope.readthedocs.io/en/stable/user/installation.html

Hypatia: 
first published version available at: 
https://hypatia-py.readthedocs.io/en/latest/installation.html

# Geographical Division of the country: 
![Sudan regions](https://user-images.githubusercontent.com/95032502/203135274-9e7c19f7-f6d3-4969-bb93-e2ab90372583.png)

# units 
For OSeMOSYS and Hypatia the following units were used:
Capacity GW.
Activity PJ.
Monetary million USD/ capacity or Activity unit.

For Calliope: 
Capacity kW.
Activity kWh.
Monetary USD/ capacity or Activity unit.

# Notes:
*In calliope the Avilability factor of conventional power plants was only considered for the existing power plants.
* The capacity factor and resource potential for solar and wind is different in the trade scenario from the BAU and phase-out Scenarios because a different criterion to assess tge potential was adapted.
