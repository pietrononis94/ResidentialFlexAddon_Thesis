# ResidentialFlexAddon_Thesis

This repository collects the first version of the BALMOREL model add-on developed for 

BALMOREL community source and home page:
https://github.com/balmorelcommunity/Balmorel
http://www.balmorel.com/index.php/contact

The add-on has been implemented as a stand alone optimization algorithm in Julia and Pyhton languages. The scope of the first is to determine the optimal load scheduling of flexible technologies (EVs and HPs). Specifically, starting from the profiles of each category, the totalflexible demand is calculated following the method applied in previous Chapter6.The flexible demand profiles are scaled by the respective number of vehicles and heatpumps actively responding to price signals, as explained further. All the total flexibledemand of each category is aggregated into two time series, one for DK1 and one forDK2, and included in Balmorel add-on inputs. These time series provide to the modelthe hourly demand deviation generated by flexible loads. In practice, this time seriesconstitute a exogenous parameter namedDERESEV HP. This parameter is readand added in Balmorel electricity demand equationQEEQ. TheDERESEV HPparameter is set for regions and allows to include the flexible residential profiles toall the regions present in the model.


Authors:
Pietro Nonis
Francesco Gaballo

Thesis project: 
Investigation of residential electricityconsumption profiles with a focus on theenergy system flexibility potential

From Denmark Technical University
Sustainable Energy
Energy System Analysis


