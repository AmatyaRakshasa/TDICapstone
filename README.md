# TDICapstone : Predicting Project Cancellation for Public Private Infrastructure Projects
# Introduction
# Data Description and Ingestion
* [PPI Database](https://ppi.worldbank.org/en/ppidata)
The Private Participation in Infrastructure (PPI) Project Database has data on over 6,400 infrastructure projects in 137 low- and middle-income countries. The database is the leading source of PPI trends in the developing world, covering projects in the energy, transport, water and sewerage, ICT backbone, and Municipal Solid Waste (MSW) sectors (MSW data includes projects since 2008) Projects include management or lease contracts, concessions, greenfield projects, and divestitures.

* [Major Episodes of Systemic Violence](http://www.systemicpeace.org/inscrdata.html)
Center for Systemic Peace, Major Episodes of Political Violence, 1946-2018 (War List), Annual Set lists annual, cross-national, time-series data on interstate, societal, and communal warfare magnitude scores (independence, interstate, ethnic, and civil; violence and warfare) for all countries.

* [EM-DAT International Disaster Database](https://www.emdat.be/)
The Centre for Research on the Epidemiology of Disasters (CRED) launched the Emergency Events Database (EM-DAT). EM-DAT was created with the initial support of the World Health Organisation (WHO) and the Belgian Government.
EM-DAT contains essential core data on the occurrence and effects of over 22,000 mass disasters in the world from 1900 to the present day. The database is compiled from various sources, including UN agencies, non-governmental organisations, insurance companies, research institutes and press agencies.

* [IMF Systemic Banking Crisis Database](https://www.imf.org/en/Publications/WP/Issues/2018/09/14/Systemic-Banking-Crises-Revisited-46232)
 Drawing on 151 systemic banking crises episodes around the globe during 1970-2017, the database includes information on crisis dates, policy responses to resolve banking crises, and the fiscal and output costs of crises.

* [World Bank Global Development Data](https://data.worldbank.org/)
The World Development Indicators is a compilation of relevant, high-quality, and internationally comparable statistics about global development and the fight against poverty. The database contains 1,600 time series indicators for 217 economies and more than 40 country groups, with data for many indicators going back more than 50 years.

* [International Telecommunication Union Country Codes](https://www.itu.int/online/mm/scripts/gensel8)
The radiocommunication division of the International Telecommunication Union uses the following letter codes to identify its member countries.
# Data Exploration
![](images/ProjectCountByRegion.png)
![](images/ProjectCountBySector.png)
![](images/ProjectCountByYear.png)
![](images/ProjectCancelled.png)
![](images/ProjectAgeAtCancellation.png)
![](images/ProjectAgeAtCancellationCount.png)
![](images/ProjectAgeAtCancellationvsContractLength.png)
![](images/ProjectTimeRemainingAtCancellation.png)
![](images/ProjectTimeRemainingAtCancellationvsContractLength.png)

# Modeling Approach
## Main Modelling Challenges
### Unbalanced Classes
### Missing Data
### Absence of Project Level Dynamic Data
## Feature Engineering
## Logistic Regression Modeling
## Decision Tree Modeling
## Random Forest Classifier
## Markov Chain Classifier
## Conclusion and Future Work
