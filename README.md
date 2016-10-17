# World Base Map
This folder contains GIS layers of   
- world countries  
- capital cities  
- world extent   

All layers are in WGS84.  

Fill an issue for questions or requests.  

## Description  
At World level, no common agreement exists as regards to World countries definition. Regarding to the main data providers at World level (UN, FAO…), the number of countries available in these databases differs. 
We document here what is and is not included in these layers.

### Territories included in the country layer  
* The country layer includes all the UN members in 2014. It concerns 193 territorial units overall the World.   
* For France, Guyane, Martinique, Guadeloupe and Reunion are aggregated to the French metropolitan territory (one multipolygon).     
* For Norway, Svalbard and Jan Meyen islands are aggregated to the Norwegian metropolitan territory (one multi polygon).   


* Beside the UN members' states, the reference layer includes 16 other territories, important to be considered regarding their respective size in term of land area and/or population and for geopolitical issues. When it is relevent the "AG" field in the shapefile indicate to which country the territory could be aggregated.   
  * New Caledonia (FR non-self-governing territory, AG = "FR")    
  * Antarctica    
  * Western Sahara (Non self-governing territory)   
  * Falkland Islands (UK non-self-governing territory, AG = "UK")   
  * Faroe Islands (DK territory, AG = "UK")   
  * Jersey (UK territory, AG = "UK")   
  * Guernsey (UK territory, AG = "UK")     
  * Greenland (DK self-governing territory, AG = "DK")    
  * Hong-Kong (CN special administrative region, AG = "CN")  
  * Macao (CN special administrative region, AG = "CN")  
  * Isle of Man (UK territory, AG = "UK")   
  * Puerto Rico (US territory, AG = "US")   
  * Palestinian territories (sovereignty unsettled)     
  * Taïwan (sovereignty unsettled)     
  * State of Vatican city  
  * Kosovo (sovereignty unsettled)    

### Capital cities
The capital layer includes capital cities location for the 193 UN Member States + Vatican city (State of Vatican city) + Laayoune (Western Sahara) + Taipei (Taïwan) + Ramallah (Palestinian territories) + Pristina (Kosovo). 

