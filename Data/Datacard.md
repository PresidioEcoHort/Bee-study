### Dataset Description


## Point of Contact: 
Diony Gamoso, dgamoso@presidiotrust.gov; dionisiogamoso@gmail.com
## Dataset Summary
This dataset has pollinator observation and specimen data and the flower genera of species they were observed visiting.  It also has flower abundance estimates and environmental conditions during sampling sessions.
The purpose is to determine the effect on pollinator abundance, diversity, and richness of augmenting landscaped planter beds with native plants. In addition, I am curious if adding host plants for specialist bees attracts them to the planters.   Also, I am interested in which plant species have the most habitat value to pollinators.

## Languages
English

## Dataset Structure
# Column headings for EcohortFieldMethodsData2023ForAnalysis Excel file
DateBlkTrtmnt	Date	Block	Treatment	CountType	Insect type	InsectGenus	InsectSpecies	Idnotes	Sex	Count	PlantGenus	PlantSpecies	Poll_nectar	Idnumber	captured?	Notes		

DateBlkTrtmnt: combines date, block, treatment to individually identify a sampling event
Date: date in this format: ex "29Apr2024"
Block:  identify the 12 blocks (each with three treatment plots) with four letter code.  For example "For Scott Community Garden" code is FSCG
Treatment: H = Host plant plots, NH = native non-host plant plots, C = Control
Insect type:  examples include bee, hoverfly, wasp, unknown
InsectGenus: genus of insect.  Example :  Bombus for bumblebees
InsectSpecies: the species of the insect.  For example "melanopygus" for Bombus melanopygus
IDnotes:
Sex: sex of insect if determinable
PlantGenus: genus of plant visited by the pollinator in that data row
PlantSpecies: species of plant visited by pollinator in that data row
Poll_nectar:  if determinable, was it gathering pollen or nectar
Idnumber:  identifies the individual specimen (either collected, or photographed)		Combines the DateBlkTrtmnt with s1, s2, s3 for specimen #,  or p1, p2, p3... for photographed then released insects.
captured? was the insect actually netted? or missed?
Notes:  general notes 				
# Example below:
24Apr2023stavnh	24-Apr-23	stav	NH	N2	Bee	Bombus	vosnesenskii			1	Fuschia			202300004		did not see pollen on legs						

#Column headings for EcohortFlowerData Excel file					
Date	Block	Trtmnt	DateBlkTrtCode	Loc	Time	Netter	AvegWindMph	TempC	Humidity	CloudCover	PercentInSun	Genus	Species	TotalOpenFl	TotalCloseFl	NatorNon	Notes				

Date: date in this format: ex "29Apr2024"
Block:  identify the 12 blocks (each with three treatment plots) with four letter code.  For example "For Scott Community Garden" code is FSCG
Treatment: H = Host plant plots, NH = native non-host plant plots, C = Control
Loc: location of sampling site; this can be an address, an intersection, or a descriptive name.  Not used in analysis
Time:  start time of sampling event in military time
Netter:  the initials of the person netting the pollinators
AvegWindMph:  average wind speed in miles per hour measured with a Kestrel
TempC:  temperature in degrees Celsius measured with Kestrel
Humidity: percent humidity measured with Kestrel
CloudCover: percent of sky covered by clouds
PercentInSun: percent of the 4-meter-square sampling quadrat in full sun (how much is not shaded)
If overcast, but there are no objects (trees or buildings) obstructing the light of the sun on the quadrat's surface area, that would be recorded as 100% PercentInSun
Genus: plant genus
Species: plant species
TotalOpenFl: # of total open flowers for an individual plant species within 4m square quadrat
TotalCloseFl: # of total closed flowers (buds that show the petal color, but the reproductive parts are still covered by the petals and are inaccessible to pollinators) for an individual plant species within the 4m square quadrat
NatorNon: native, ornamental, weedy to descripe plant type
Notes: general notes

# Example data
21Aug2023	mpsu	h	21Aug2023mpsuh	Powderhouse	935	DG	2	18.4	96	98	100	Grindelia	stricta	3	2	native					

# Note
One of the main goals of the research is to gather data on pollinator use of particular plants.  Hence, each row links the pollinator to the plant it was using.  Also, flower abundance and its effect on pollinator abundance, diversity , and richness are of interest, and therefore the two spreadsheets "EcoHortFlowerData" and "EcohortFieldMethodsData2023ForAnalysis" are linked through the DateBlkTrtmnt column.

## Source Data
Data was all collected in the field, at the Presidio, San Francisco.

## Initial Data Collection and Normalization

Data were collected in the field, in the Presidio, San Francisco, CA   USA.  
Bee sampling was typically conducted between 0930 - 1730, and in temperatures above 11 degrees Celsius, and average wind below 7 miles per hour.
All plant genera or species (when possible to identify) that were in bloom were recorded within the 4-meter-square quadrat, and their open and closed flowers were counted individually, or estimated (e.g. counting number of flowers on 3 inflorescences, average that number, and multiplying by the number of infloresces of that plant)  Then we would perform a 1-minute visual "snapshot" count of pollinators and which plants they were using. AFter that, we would do netting of pollinators "N1" for five minutes, and then a second 5-minute netting session "N2" , again recording which plant each pollinator was using.  We would stop the timer each time a pollinator was captured and processed.  Smaller bees were euthanized in soapy vials and collected.  Larger bees such as bumble bees were chilled in a cooler, photographed, and released.


## Social Impact of Dataset
The study seeks to measure the impact of relatively small native plant additions to ornamental planter beds (65 plants, of 7-8 species) on pollinator abundance, diversity, and richness using those plots.  Small scale additions like these are do-able by individuals, schools, cities, campuses.  Data on its impact may motivate people to plant pollinator-friendly plants in urban spaces, both increasing habitat for them, and connecting people with nature.


## Discussion of Biases
One potential bias is that observers may disproportionately look at the native plants (or other plants they think should attract pollinators) and therefore observe and capture more pollinators on those plants.   Also, observers may tend to net more unusual, or harder-to-identify bees, which may bias the data towards these types.  To counter the plant-observation bias, observers were told to try to evenly observe all plants during sampling periods.  Regarding the bias towards smaller, or harder-to-identify bees,  if multiple bees are observed within the quadrat simultaneously, observers were told to catch the harder-to-identify ones, first.  However, during the 11 minute sampling period, we have tended to get an opportunity to capture most of the pollinators visiting the plot during that time.

## Other Known Limitations
We did capture and photograph a significant number of hoverflies.  We do not yet have the expertise to identify them all, and are seeking assistance. 

### Additional Information
## Dataset Curators
Diony Gamoso (Presidio Trust)
Mya Esquivel (Presidio Trust)
Naomi de la Torre (Presidio Trust)

Funding provided by the Presidio Trust




