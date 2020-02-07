This is a consulting project by City of Toronto. Toronto’s **Vision Zero** initiative is a road safety plan focused on reducing traffic-related fatalities and serious injuries. The main aim of this project is to predict traffic collision and understand the causes of crashes, which could finally provide the authorities with some useful insights to reduce injuries and fatalities on the city’s streets by taking actions such as:
- Emergency vehicle allocation
- Roadway design
- Where to place additional signs (e.g. warning for curves, speed limit)
- Safe route planning (e.g. for hazmat transportation)
  
### Description of Data
1. The dataset form City of Toronto contains collision occurrences and the actions and outcomes for individuals involved in them from 2000 - 2019.  The data is approximately 2.6 million rows by 38 columns.  Columns include the longitude/latitude of collisions, time of day, day of year, road conditions (wet, dry), actions taken by road users (e.g. driver going straight, driver turning, pedestrian crossing street), injuries sustained, etc.  An incomplete data dictionary can be found here: https://github.com/CityofToronto/vz_challenge/tree/master/transportation/collisions#data-dictionary

	* The data ingestion pipeline for collisions comes from multiple sources with multiple degrees of data accuracy (and processing speeds) – the fatalities and serious injuries come from Toronto Police Services (TPS), while minor injury and property damage only collisions come from the Collision Reporting Centre (CRC).

2. Boundaries of City of Toronto Neighbourhoods. It contains the name and geometry information of 140 neighbourhoods located in Toronto.