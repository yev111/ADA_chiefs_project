# Title

# Abstract
One’s housing situation is a personal issue and often reflects or determines our style of living. Evolving lifestyles and demographic change evoke the question of future housing concepts [1,2].
This data study aims at analyzing how people live based on the number of people living per household in Switzerland. Do location, housing prize, income, demographic affiliation or even political orientation influence the number of people we are living with? Diverse Data provided by the Federal Statistical Office of Switzerland between 2010 and 2017 are analyzed on communal level. General trends are discovered and the spatial dependence analyzed. Hypotheses on the influence of different factors are then tested by means of statistical correlation analysis. The final goal is to realize a convincing visualization on a blog to present the key findings.

*[1]:https://www.srf.ch/news/panorama/drei-megatrends-veraendern-das-wohnen*
*[2]:https://www.beobachter.ch/wohnen/miete/wohnverhalten-die-bleibe-der-zukunft*

# Research questions
Are there any overall trends in the number of people living per houshold(p/HH)?
Furthermore, the influence of the following factors on p/hh are tested:
    - housing price
    - income
    - location (urban, rural)
    - political orientation
    - demographic affilation (age, nationality, job)
    
Do they enforce the trends or have direct correlations? Have income levels kept pace with rent prices over the years or has one parameter outpaced the other and if so, is it Swiss-wide or focused on uban/rural areas, and what impact does it have on the household size?  

# Dataset
Some datasets were split between the following 7 big Swiss regions:
    - Lake Geneva Region (VD, VS, GE)
    - Espace Mittelland (BE, FR, SO, NE, JU)
    - Northwestern Switzerland (BS, BL, AG)
    - Central Switzerland (LU, UR, SZ, OW, NW, ZG)
    - Zurich (ZH)
    - Eastern Switzerland (GL, SH, AR, AI, SG, GR, TG)
    - Ticino (TI)

The following dataset was selected for the time span between 2010 - 2017 (not all data sets were available in the desired time-span):
    - Permanent resident population in private households by commune and household size (2010-2017)
    - Structure of the permanent resident population by canton (2010-2017)
    - Household size in the biggest agglomerations and rural areas (Haushaltsgrösse in den grössten Agglomerationen und in den ländlichen Gebieten) (2011-2017)
    - Average rent in Swiss francs based on age demographics and size of apartment by big Swiss regions (Durchschnittlicher Mietpreis in Franken nach Altersgruppe der Haushaltsmitglieder und Zimmerzahl, nach Grossregionen) (2011-2013)
    - Average rent in Swiss francs based on age demographics by big Swiss regions (Durchschnittlicher Mietpreis in Franken nach Altersgruppe der Haushaltsmitglieder und Grossregionen) (2013-2016)
    - Average rent in Swiss francs based on nationality of the household members and household size (Durchschnittlicher Mietpreis in Franken nach Nationalität der Haushaltsmitglieder und Zimmerzahl, nach Grossregionen) (2012-2016)
    - Average rent in Swiss francs based on apartment size for the 10 biggest Swiss cities (Durchschnittlicher Mietpreis in Franken nach Zimmerzahl für die 10 grössten Städte) (2012-2014)
    - Average rent in Swiss francs based on construction period and apartment size(Durchschnittlicher Mietpreis in Franken nach Bauperiode und Zimmerzahl, nach Grossregionen) (2010-2016)
    Swiss regions
    - Rent per square meter in Swiss francs (Mietpreis pro Quadratmeter (in CHF) 1) pro Privathaushalt) (2012-2016)
    - Gross monthly wage (median and quartile range), Swiss and foreigners, by professional position and gender. Private and public (Confederation, cantons, districts, communities, corporations) sectors combined (2008-2016)
    - Gross monthly wage (median and quartile range), Swiss and foreigners, professional position and gender (2008-2016), based on big Swiss region 
    - Cantonal parlamentary voting (Kantonale Parlamentswahlen: Parteistärken mit Zuteilung der Mischlisten auf die Parteien) (2010-2017)

All the mentioned data sets were acquired from opendata.swiss. The expactation is to get a sense of different households and get trends on the size of them based on rent price, immigration status and the average income on the area. For instance, it is common knowledge that the population density increases the closer you get to big cities. One reason is because the rent price increases in big cities, so household sizes increase to split the rental cost. However, we would like to analyze the households from a social perspective: Has there been a shift in household size in the past years? For instance, the foreign population in the canton of Zurich has increase from 330,000 to 402,000 between 2010 and 2017, an increase of over 70,000. The Lake Geneva region has seen a similar incrase in foreigners during the same period. Are foreigners more likely to live in bigger households and if so, is it because they earn less money or could it be other reasons? Another example is that between 2010 and 2017, the population living in 1-person household in the city of Zurich decreased from 92,000 to 88,700, while the 3-person household increased from 58,000 to 70,500. While in the city of Winterthur, all households increased between 2010 and 2017. Our group would like to analyze these differences based on social aspects like income levels, immigration status and rent prices, and where possible also age demographics. 

The data size would be desireably between 2010 an 2017, based on canton or the 7 big Swiss regions, and possibly based on communes. 

# A list of internal milestones up until project milestone 2
Add here a sketch of your planning for the next project milestone.

# Questions for TAa
    - Is there a GIS we could obtain to be able to zoom into each building of each Swiss commune and get data of the household of that building, like how many people live in the building and the size of the apartment?
    - Is there a way to obtain average income levels, Swiss and foreigners, for each commune as opposed to the big Swiss region?
