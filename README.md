# Demography behind household sizes in Switzerland and its change in time

# Abstract
One’s housing situation is a personal issue and often reflects or determines our style of living. Evolving lifestyles and demographic change evoke the question of future housing concepts [1,2].
<br />
This data study aims at analyzing how people live based on the number of people living per household in Switzerland. Do location, housing prize, income, demographic affiliation or even political orientation influence the number of people we are living with? Diverse Data provided by the Federal Statistical Office of Switzerland between 2010 and 2017 are analyzed on communal level. General trends are discovered and the spatial dependence analyzed. Hypotheses on the influence of different factors are then tested by means of statistical correlation analysis. The final goal is to realize a convincing visualization on a blog to present the key findings.
<br />
<br />
*[1]:https://www.srf.ch/news/panorama/drei-megatrends-veraendern-das-wohnen*
<br />
*[2]:https://www.beobachter.ch/wohnen/miete/wohnverhalten-die-bleibe-der-zukunft*
<br />
<br />

# Research questions
- Is there a correlation between the foreign population in Switzerland and the number of people living per household (p/HH)?
 <br />
 - Is there a correlation between the level of income and the size of the household?
 <br />
There can be various factors that might affect the outcome and hence need to be taken into account when doing the research:
<br />
<br />
    - housing price
    <br />
    - income classes
    <br />
    - location (urban, rural)
    <br />
    - demographic affilation (age, nationality, job)
    <br />
    <br />
Do they enforce the trends or have direct correlations? Have income levels kept pace with rent prices over the years or has one parameter outpaced the other and if so, is it Swiss-wide or focused on urban/rural areas, and what impact does it have on the household size? Differences between Swiss and foreigners, such as income levels and rental prices, for instance, are also considered. 

# Dataset
Not all datasets have the same geographical resolution. We try to analyze the most possible on a communal scale, but we also have inputs on cantonal levels and some datasets were split between the following 7 big Swiss regions:
<br />
<br />
    - Lake Geneva Region (VD, VS, GE)
    <br />
    - Espace Mittelland (BE, FR, SO, NE, JU)
    <br />
    - Northwestern Switzerland (BS, BL, AG)
    <br />
    - Central Switzerland (LU, UR, SZ, OW, NW, ZG)
    <br />
    - Zurich (ZH)
    <br />
    - Eastern Switzerland (GL, SH, AR, AI, SG, GR, TG)
    <br />
    - Ticino (TI)
<br />
<br />
The following datasets were selected for the time span between 2010 - 2016. If a data set is not within the desired period, then forcasting models will be applied. If such models are used, these will be specifically highlighted to make readers aware of them.
<br />
<br />
    - Permanent resident population in private households by commune and household size (2010-2017)
    <br />
    - Structure of the permanent resident population by canton (2010-2017)
    <br />
    - Household size in the biggest agglomerations and rural areas (Haushaltsgrösse in den grössten Agglomerationen und in den ländlichen Gebieten) (2011-2017)
    <br />
    - Average rent in Swiss francs based on age demographics and size of apartment by big Swiss regions (Durchschnittlicher Mietpreis in Franken nach Altersgruppe der Haushaltsmitglieder und Zimmerzahl, nach Grossregionen) (2011-2013)
    <br />
    - Average rent in Swiss francs based on age demographics by big Swiss regions (Durchschnittlicher Mietpreis in Franken nach Altersgruppe der Haushaltsmitglieder und Grossregionen) (2013-2016)
    <br />
    - Average rent in Swiss francs based on nationality of the household members and household size (Durchschnittlicher Mietpreis in Franken nach Nationalität der Haushaltsmitglieder und Zimmerzahl, nach Grossregionen) (2012-2016)
    <br />
    - Average rent in Swiss francs based on apartment size for the 10 biggest Swiss cities (Durchschnittlicher Mietpreis in Franken nach Zimmerzahl für die 10 grössten Städte) (2012-2014)
    <br />
    - Rent per square meter in Swiss francs (Mietpreis pro Quadratmeter (in CHF) 1) pro Privathaushalt) (2012-2016)
    <br />
    - Gross monthly wage (median and quartile range), Swiss and foreigners, by professional position and gender. Private and public (Confederation, cantons, districts, communities, corporations) sectors combined (2008-2016)
    <br />
    - Gross monthly wage (median and quartile range), Swiss and foreigners, professional position and gender (2008-2016), based on big Swiss region
    <br />
    - Cantonal parlamentary voting (Kantonale Parlamentswahlen: Parteistärken mit Zuteilung der Mischlisten auf die Parteien) (2010-2017)
    <br />
    <br />
Dataset for visualization of the Swiss map:
    <br />
    <br />
    - Swiss cantonal topojson json file
    <br />
    - Swiss communal geojson
<br />
<br />
All the mentioned data sets were acquired from opendata.swiss. The expectation is to get a sense of different households and get trends on the size of them based on rent price, immigration status and the average income of the area, and analyze discrpeancies between Swiss and foreign residents. The group would like to analyze the households from a social perspective: Has there been a shift in household size in the past years? For instance, the foreign population in the canton of Zurich has increased from 330,000 to 402,000 between 2010 and 2017, an increase of over 70,000. The Lake Geneva region has seen a similar incrase in foreigners during the same period. Are foreigners more likely to live in bigger households and if so, is it because they earn less money or could it be aother reasons? Another example is that between 2010 and 2017, the population living in 1-person household in the city of Zurich decreased from 92,000 to 88,700, while the 3-person household increased from 58,000 to 70,500. While in the city of Winterthur, all households increased between 2010 and 2017. Our group would like to analyze these differences based on social aspects like income levels, immigration status and rent prices.
<br />
<br />
The data size would be desireably between 2010 and 2016, based on canton or the 7 big Swiss regions. Meanwhile, when available, we try to focus on a communal resolution. 
<br />
# Objectives for the next milestone 3 on 16.12.2018.
<br /> - Thorough analysis to address the hypothesis based on different factors outlined earlier
<br /> - Analysis should have visualization based on statistical outcome 
<br /> - Display of regional outcomes on a Swiss map for better depiction of regional factors of the hypothesis
<br /> - Write a report based on the findings and discuss those findings
<br /> - Brainstorming about ideas of how to design the poster for the prentation and assign logistics to group members 
# Questions for TAs
<br /> - The "communes.geojson" file that has all the coordinates of each commune is 90MB large and while it loads into jupyter notebooks, it does not display the borders when adding it to a Swiss map. This is likely to a large file. Is there a way to display the borders anyways using the GeoJSon? If so, how?
