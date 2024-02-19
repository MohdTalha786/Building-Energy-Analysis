# Building-Energy-Analysis
An approach to breakdown the concept that how we going to achieve the particular building requirement as per the previous/given datadata
Background
Energy use (say KWh), energy demand (say KW), and occupant thermal comfort (to an extent) are a function of location, building envelope (wall, roof and windows) configuration (orientation, solar exposure, material properties, etc.), efficiency of energy systems (cooling systems, lighting systems, etc.), and building use.
Intent
From a dataset of building simulation models, we would like to predict the energy use, demand and occupant thermal comfort of any given building.
Data points (for each building)

Inputs


Building use: Typology          


Location: Climate, latitude, longitude            


Building geometry/form & orientation            

Aspect Ratio        

Orientation     

Building Areas (Floor area of air-conditioned spaces)      

Product of Material Conductance and Environment Exposed Areas (U*A)...etc.     

Lighting systems  

Installed lighting in watts per square feet (say 2 18W LED tubes in 100 SF space is 0.36 W/SF)     

Equipment         

Installed equipment in watts per square feet       

HVAC Systems (implies air conditioning and heating systems)   

Capacity      

Efficiency



Outcomes         

   
   Annual Energy Use      
   
   
   
   Peak Energy Demand





Metrics



Energy Use Intensity (Watt-hour/ Square Feet - Year)
Peak Energy Demand (Watts)
Envelope Gain (Watts/Square Feet)




Problem Statements





Develop a data structure that will serve as a database for machine learning models. It need not be comprehensive, but should be able to conceptually explain Problem Statement 2.





2-Explain briefly the conceptual working of ML (irrespective of chosen model). Explicitly identify how you will identify key parameters that influence energy use or demand and what will be the basis of this determination.




3-How do you plan to go about doing this in the span of 2 months?







4-Can you suggest an ML algorithm and dataset size (number of records) required for successful implementation of ML models? (Optional).
