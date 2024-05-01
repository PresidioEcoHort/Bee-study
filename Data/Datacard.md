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
Example below:
24Apr2023stavnh	24-Apr-23	stav	NH	N2	Bee	Bombus	vosnesenskii			1	Fuschia			202300004		did not see pollen on legs						

#Column headings for EcohortFlowerData Excel file					
Date	Block	Trtmnt	DateBlkTrtCode	Loc	Time	Netter	AvegWindMph	TempC	Humidity	CloudCover	PercentInSun	Genus	Species	TotalOpenFl	TotalCloseFl	NatorNon	Notes				

Date: date in this format: ex "29Apr2024"
Block:  identify the 12 blocks (each with three treatment plots) with four letter code.  For example "For Scott Community Garden" code is FSCG
Treatment: H = Host plant plots, NH = native non-host plant plots, C = Control
Loc: location of sampling site; this can be an address, an intersection, or a descriptive name.  Not used in analysis
Time:  start time of sampling event in military time
Netter:  the initials of the person netting the pollinators
AvegWindMph:  average wind speed measured with a Kestrel
TempC:  temperature in degrees Celsius measured with Kestrel
Humidity: percent humidity measured with Kestrel
CloudCover: percent of sky covered by clouds
PercentInSun: percent of the actual 4-meter-square sampling quadrat in full sun (how much is not shaded)
If overcast, but there are no objects (trees or buildings) obstructing the light of the sun on the quadrat's surface area, that would be recorded as 100% PercentInSun
Genus: plant genus
Species: plant species
TotalOpenFl: # of total open flowers for an individual plant species within 4m square quadrat
TotalCloseFl: # of total closed flowers (buds that show the petal color, but the reproductive parts are still covered by the petals and are inaccessible to pollinators) for an individual plant species within the 4m square quadrat
NatorNon: native, ornamental, weedy to descripe plant type
Notes: general notes

Example data
21Aug2023	mpsu	h	21Aug2023mpsuh	Powderhouse	935	DG	2	18.4	96	98	100	Grindelia	stricta	3	2	native					

# Note
One of the main goals of the research is to gather data on pollinator use of particular plants.  Hence, each row links the pollinator to the plant it was using.  Also, flower abundance and its effect on pollinator abundance, diversity , and richness are of interest, and therefore the two spreadsheets "EcoHortFlowerData" and "EcohortFieldMethodsData2023ForAnalysis" are linked through the DateBlkTrtmnt column.

## Source Data
Data was all collected in the field, at the Presidio, San Francisco.

## Initial Data Collection and Normalization
Describe the data collection process. Describe any criteria for data selection or filtering. List any key words or search terms used. If possible, include runtime information for the collection process.
Data were collected in the field, in the Presidio, San Francisco, CA   USA.  
Bee sampling was typically conducted between 0930 - 1730, and in temperatures above 11 degrees Celsius, and average wind below 7 miles per hour.
All plant genera or species (when possible to identify) that were in flower were recorded within the 4-meter-square quadrat, and their open and closed flowers were counted individually, or estimated (e.g. counting number of flowers on 3 inflorescences, average that number, and multiplying by the number of infloresces of that plant)  Then we would perform a 1-minute "snapshot" count of pollinators and which plants they were using. AFter that, we would do netting of pollinators "N1" for five minutes, and then a second netting session "N2" .  We would stop the timer each time a pollinator was captured and processed.  Smaller bees were euthanized in soapy vials and collected.  Larger bees such as bumble bees were chilled in a cooler, photographed, and released.


Social Impact of Dataset
Please discuss some of the ways you believe the use of this dataset will impact society.

The statement should include both positive outlooks, such as outlining how technologies developed through its use may improve people's lives, and discuss the accompanying risks. These risks may range from making important decisions more opaque to people who are affected by the technology, to reinforcing existing harmful biases (whose specifics should be discussed in the next section), among other considerations.

Also describe in this section if the proposed dataset contains a low-resource or under-represented language. If this is the case or if this task has any impact on underserved communities, please elaborate here.

Discussion of Biases
Provide descriptions of specific biases that are likely to be reflected in the data, and state whether any steps were taken to reduce their impact.

For Wikipedia text, see for example Dinan et al 2020 on biases in Wikipedia (esp. Table 1), or Blodgett et al 2020 for a more general discussion of the topic.

If analyses have been run quantifying these biases, please add brief summaries and links to the studies here.

Other Known Limitations
If studies of the datasets have outlined other limitations of the dataset, such as annotation artifacts, please outline and cite them here.

Additional Information
Dataset Curators
List the people involved in collecting the dataset and their affiliation(s). If funding information is known, include it here.

Licensing Information
Provide the license and link to the license webpage if available.

Citation Information
Provide the BibTex-formatted reference for the dataset. For example:

@article{article_id,
  author    = {Author List},
  title     = {Dataset Paper Title},
  journal   = {Publication Venue},
  year      = {2525}
}
If the dataset has a DOI, please provide it here.

Contributions
Thanks to @github-username for adding this dataset.
