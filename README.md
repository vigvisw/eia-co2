# EIA Open Data - US CO2 Emissions Dataset

A simple tool for collecting, and preprocessing US state level CO2 Emissions data available through [EIA's Open Data API](https://www.eia.gov/opendata/). 

The preprocessed dataset incudles the following features.

#### Features 
* ```state```:  State associated with the CO2 emissions data
	* In addition to the 50 states, this feature also captures Washington D.C, and the full U.S.A
* ```sector```: A group of major energy-consuming components of U.S. society developed to measure and analyze energy use. The sectors most commonly referred to in EIA are: **residential, commercial, industrial, transportation, and electric power**.
	* **Residential sector:** An energy-consuming sector that consists of living quarters for private households. Common uses of energy associated with this sector include space heating, water heating, air conditioning, lighting, refrigeration, cooking, and running a variety of other appliances. The residential sector excludes institutional living quarters
	* **Commercial sector:** An energy-consuming sector that consists of service-providing facilities and equipment of businesses; Federal, State, and local governments; and other private and public organizations, such as religious, social, or fraternal groups. The commercial sector includes institutional living quarters. It also includes sewage treatment facilities. Common uses of energy associated with this sector include space heating, water heating, air conditioning, lighting, refrigeration, cooking, and running a wide variety of other equipment. Note: This sector includes generators that produce electricity and/or useful thermal output primarily to support the activities of the above-mentioned commercial establishments.
	* **Industrial sector:** An energy-consuming sector that consists of all facilities and equipment used for producing, processing, or assembling goods. The industrial sector encompasses the following types of activity manufacturing (NAICS codes 31-33); agriculture, forestry, fishing and hunting (NAICS code 11); mining, including oil and gas extraction (NAICS code 21); and construction (NAICS code 23). Overall energy use in this sector is largely for process heat and cooling and powering machinery, with lesser amounts used for facility heating, air conditioning, and lighting. Fossil fuels are also used as raw material inputs to manufactured products. Note: This sector includes generators that produce electricity and/or useful thermal output primarily to support the above-mentioned industrial activities.
	* **Transportation sector:** An energy-consuming sector that consists of all vehicles whose primary purpose is transporting people and/or goods from one physical location to another. Included are automobiles; trucks; buses; motorcycles; trains, subways, and other rail vehicles; aircraft; and ships, barges, and other waterborne vehicles. Vehicles whose primary purpose is not transportation (e.g., construction cranes and bulldozers, farming vehicles, and warehouse tractors and forklifts) are classified in the sector of their primary use.
	* **Electric power sector:** An energy-consuming sector that consists of electricity only and combined heat and power(CHP) plants whose primary business is to sell electricity, or electricity and heat, to the public--i.e., North American Industry Classification System 22 plants.
* ```fuelType```: Any material substance that can be consumed to supply heat or power.
	* coal
	* coal (electric utility)
	* natural gas
	* natural gas (pipeline)
	* petroleum
	* petroleum coke
	* asphalt and road oil
	* aviation gasoline
	* residential
	* industrial coking
	* industrial other
	* distillate fuel
	* lpg (fuel use)
	* jet fuel
	* kerosene
	* lubricants
	* motor gasoline
	* residual fuel
	* all fuels
* ```year```: Year associated with the CO2 emission data
	*	All years between 1980 - 2018 
* ```CO2Emission```: Metric ton CO2
	 