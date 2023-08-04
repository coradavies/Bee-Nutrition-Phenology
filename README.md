# Bee-Nutrition-Phenology
Code and data associated with Temporal overlap of native bee assemblages with pollen protein density in forest canopy gaps is mediated by bee body size.

DATA FILES  
__________
The following provides information for all data files included in this data repository.   
The data was collected from May-August 2021 by Cora Davies.   

Bradford - folder containing data from Bradford Assays (see "Bradford" text file for more information).  

BeeCaptures - Data for observed bee-flower interactions.   
	- ID: unique ID number  
	- Date: Date observed  
	- Day: day of calendar year observed  
	- Site: Site number  
	- Sample: sample period number  
	- DayTime: time of day sampled  (1= 8am-11am; 2= 11am-2pm; 3= 2pm-5pm)  
	- Flower: Species of flower observed  
	- Bee: Species of bee observed  
	- Family: Family of bee observed  
	- Genus: Genus of bee observed  
	- Species: Species of bee observed if certain  
	- Species2: Species of bee observed, best guess  
	- CaptureTime: Time of observation (minutes from start of sampling period)  

BeeNutrtionMismatch_Code - Contains code for all data analyses  

BeeSampleTimes - Details for date and times bees were observed.   
	- Date: Date observed  
	- Site: Site number  
	- Sample: Sample number  
	- Time: Time sampled (1= 8am-11am; 2= 11am-2pm; 3= 2pm-5pm)  
	- Start: Start time  
	- End: End time  
	- Temp: Temperature (C) at start of sampling period  

FloralAbundance - Data of floral abundance along belt transects.  
	- Date: Date recorded  
	- Day: Day of calendar year  
	- Site: Site number  
	- Sample: Sample number  
	- Transect: Transect number (1,2,3)  
	- Species: Flower species  
	- Count: Total number of inflorescences in belt transect  

FloralMeasurements - contains data of floral visual traits  
	- Date: Date collected (if blank, species was not collected)  
	- Species: Flower species  
	- Number: Flower sample number (1-5)  
	- Height: Height of flower from ground (mm)  
	- UV: UV reflective patterns present (yes/no)  
	- Photo: was a photo of flower taken (yes/no)  
	- Color: color of flower (Blue/White/Yellow)  
	- Size: Size of corolla  
	- Red: red value  
	- Green: green value  
	- Blue: blue value  
  
GenusTraits - contains data of bee genera functional traits  
	Genus - bee genera  
	Size - size of bee: small, mid, large (relative to Apis mellifera)  
	Nest1 - nesting location  
		above = above ground  
		below = below ground  
		both = both above and below ground, including kleptoparasitic behavior  
	Nest2 - nesting strategy/construction  
		excavate = excavate  
		rent = rent  
		klepto = kleptoparasitic behavior  
	Sociality - sociality of bee genus  
		multiple = varies between species within the genus    
		solitary = solitary behavior   
		social = social behavior  
		klepto = kleptoparasitic behavior  
	Lecty - diet breadth  
		multiple = varies between species within the genus  
		poly = polylectic (wide diet breadth)  
		oligo = oligolectic (narrow diet breadth)  
		klepto = kleptoparasitic behavior  

PollenMass- recorded measurements of pollen mass  
	- Label: specimen label  
	- Number: specimen number   
	- Collection: Date collected  
	- Species: Flower species  
	- Count: number of flowers collected  
	- Mass: Mass of pollen sample  


SiteInformation - Details for site locations.   
	- Site: Site number  
	- Location: Site location (1 = Pole Hill; 2 = Big Elk Meadow)  
	- Azimuth: The Azimuth of the three belt transects (degrees)  
	- Elevation: Site elevation (meters)  
	- Size: Size of meadow (hectares)  
	- T1Lat: Latitude of transect 1 (decimal degrees)  
	- T1Long: Longitude of transect 1 (decimal degrees)   
	- T2Lat: Latitude of transect 2 (decimal degrees)  
	- T2Long: Longitude of transect 2 (decimal degrees)   
	- T3Lat: Latitude of transect 3 (decimal degrees)  
	- T3Long: Longitude of transect 3 (decimal degrees)   
