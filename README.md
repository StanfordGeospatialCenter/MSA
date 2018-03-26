

## **Status of the database**  

***Due to the significant resource requirements for maintaining this dataset, the Stanford Mass Shootings in America database has been permanently suspended. The project has been archived and will remain publicly available as a GitHub repository.***  

***As a service to those seeking a comparable and more recently updated alternative, we are providing links to other, more active efforts, below. The Stanford Geospatial Center in no way warrants the quality of, nor endorses any of the database efforts linked to in the following list and provided the links only as a starting point to what should be a measured and careful selection process when seeking data on phenomena of this type.***  


# **MSA (Mass Shootings in America)**  

A repository for the maintenance and distribution of the Mass Shootings in America Database.

#### Contents

**Data Folder** contains the most updated MSA dataset as .csv and GeoJSON

**Methodology Folder** contains the rules for how events are included into the dataset and how it is organized.

# Project background
The Stanford Mass Shootings of America (MSA) data project was begun in 2012 in reaction to the mass shooting in Sandy Hook, CT. In our initial attempts to map this phenomena it was determined that no comprehensive collection of these incidents existed online. The Stanford Geospatial Center set out to create, as best we could, a single point repository for as many mass shooting events as could be collected via online media. The result was the Stanford MSA.

### What the Stanford MSA is
The Stanford MSA is a data aggregation effort. It is a curated set of spatial and temporal data about mass shootings in America, taken from online media sources. It is an attempt to facilitate research on gun violence in the US by making raw data more accessible.

### What the Stanford MSA is not
The Stanford MSA is not a comprehensive, longitudinal research project. The data collected in the MSA are not investigated past the  assessment for inclusion in the database. The MSA is not an attempt to answer specific questions about gun violence or gun laws.

The Stanford Geospatial Center does not provide analysis or commentary on the contents of this database or any derivatives produced with it.

### Data collection methodology
The information collected for the Stanford MSA is limited to online resources. An initial intensive investigation was completed looking back over existing online reports to fill in the historic record going back to 1966.  Contemporary records come in as new events occur and are cross referenced against a number of online reporting sources.  In general a minimum of three corroborating sources are required to add the full record into the MSA (as many as 6 or 7 sources may have been consulted in many cases). All sources for each event are listed in the database.

Due to the time involved in vetting the details of any new incident, there is often a 2 to 4 week lag between a mass shooting event and its inclusion in the public release database.

It is important to note the records in the Stanford MSA span a time from well before the advent of online media reporting, through its infancy, to the modern era of web based news and information resources. Researchers using this database need to be aware of the reporting bias these changes in technology present.  A spike in incidents for recent years is likely due to increased online reporting and not necessarily indicative of the rate of mass shootings alone.  Researchers should look at this database as a curated collection of quality checked data regarding mass shootings, and not an exhaustive research data set itself. Independent verification and analysis will be required to use this data in examining trends in mass shootings over time.

### Definition of Mass Shooting
The definition of mass shooting used for the Stanford database is 3 or more shooting victims (not necessarily fatalities), not including the shooter. Identifiably gang, drug or organized crime related shootings are not included in the database. 

#### Why limit the type of incidents added to the Stanford MSA?
The goal of the Stanford MSA is to track the particular phenomena of mass shootings in the U.S. and not gun violence as a whole. While all gun violence is tragic, it is the seemingly spontaneous shooting incidents that are the most confounding when looking for answers about motivation, after the fact.

#### Differences between the Stanford MSA and other mass shooting data projects
The key difference between the Stanford MSA and other similar projects is the scope of definition and the focus on mass shooting incidents versus mass murder. Instead of limiting our data collection to incidents in which 4 or more fatalities occurred (the FBI definition for Mass Murder), we instead collect incidents of 3 or more shooting victims (not necessarily fatalities). All mass shooting definitions are arbitrary in that there is no natural way to quantify such an event. In setting up our threshold we wanted to focus on the shootings over the outcomes.

#### How to compare the Stanford MSA totals to other project totals for 'Mass Shootings'
There are a number of other databases tracking shootings in the U.S. each with their own criteria and incident tally. Extreme differences between datasets are likely an indication of different thresholds for inclusion (1, 2, 3 or 4 victims), the type of outcome (fatalities only versus fatalities and injuries), and the type of incidents captured (all gun violence, gang related, domestic, terroristic, etc.).

##### Known issues
- Data for the Stanford MSA are collected and maintained with the help of student assistants, interns, or temporary staff. The database may be left untended for short periods between staff hires during which events may go unrecorded and remain unremediated when work on the MSA resumes.

- Locations in the MSA are generally given as City/State. When using some online mapping services to geocode locations by City/State some locations may be misplaced due to the repetition of common city names between multiple states. This is an issue with the mapping service, not the database. Double check any maps created with this data to be sure your chosen service is placing locations correctly.

- Sources for the MSA come solely from online reports. Increases in records over time can not simply be assumed to be a reflection of increased events as online reporting trends and outlets have increased tremendously over the span of time covered by the Stanford MSA.
 
- Some shooting incidents defy straightforward classification. Ambiguous records are flagged with a value of 2 in the depreciation field. For a more detailed explanation, see data dictionary in the [Methodology folder](https://github.com/StanfordGeospatialCenter/MSA/tree/master/Methodology).

##### A note to researchers and journalists using the MSA
It is the user's responsibility to perform their own rigorous data quality assessment before using the MSA in their work.  Please read the data dictionary completely when looking for incident breakdown information. Please refer to the Known Issues and Methodology sections above for information on other issues that may affect trends in the data. Graphing the raw data for commentary without adjusting for the various known issues and methodology (see above sections) may not provide insightful information.

##### How to cite the MSA
The Stanford MSA is released under a Creative Commons Attribution 4.0 international license. Please cite the MSA as “Stanford Mass Shootings in America, courtesy of the Stanford Geospatial Center and Stanford Libraries”.

##### Status of the database
Due to the significant resource requirements for maintaining this dataset, the Stanford Mass Shootings in America database has been permanently suspended. The project has been archived and will remain publicly available as a GitHub repository.

