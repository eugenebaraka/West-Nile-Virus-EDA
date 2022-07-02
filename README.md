# West Nile Virus EDA

In this repo, I conduct an Exploratory Data Analysis on the subset of the Western Nile Virus dataset found on [Kaggle](https://www.kaggle.com/competitions/predict-west-nile-virus/data).

West Nile Virus (WNV) is a viral illness largely spread by mosquitoes. The disease is transmitted to a person when an infected mosquito bites them.

The city of Chicago, Illinois has been keeping track of mosquito populations and WNV prevalence using a series of traps that they place around the city. They are then able to study the captured specimens and monitor the state of WNV spread in the city.


Year: Year that the WNV test is performed			
Week: Week that the WNV test is performed			
Address: Block	Address of the location of trap.			
Block: Block number of address			
Trap: Id of the trap		
Trap type: Type of trap			
Date: Date and time that the WNV test is performed. 	
Mosquito number: Number of mosquitoes caught in this trap. Capped at 50, when the number of mosquitoes exceed 50, they are split into another record (another row in the dataset)
Mosquito ID: Id for Mosquito species			
WNV Present: Whether West Nile Virus was present in these mosquitos		
Species: Mosquito species			
Lat: Latitude of trap			
Lon: Longitude of trap		
