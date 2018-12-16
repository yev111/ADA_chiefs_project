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
- Is there a correlation between the foreign population in Switzerland and the number of people living per household (p/HH)
- Is there a correlation between the level of income and the size of the households?

There can be various factors that might affect the outcome and hence need to be taken into account when investigating those two statements:
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

# Datasets

The datasets containing our response variable (distribution of household sizes) will be in the focus for all final analyses ("hh_sizeXXXX"). Also, the dataset "incomes" is crucial, as it provides a communal resolution for the incomes and for some demographic properties. As it dates from 2007, it has to be extrapolated and adapted, using other, available datasets. 

The mostpart of the other layers do unfortunately not have the same geographical resolution. We try to analyze the most possible on a communal scale, but we also have inputs on cantonal levels and some datasets were split between the following 7 big Swiss regions:
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
    - Gross monthly wage (median and quartile range), Swiss and foreigners, by professional position and gender. Private and public (Confederation, cantons, districts, communities, corporations) sectors combined (2008-2016)
    <br />
    - Gross monthly wage (median and quartile range), Swiss and foreigners, professional position and gender (2008-2016), based on big Swiss region
    <br />
    - Demographics of Switzerland per municipality, general (around 2016)
    <br />
    - Mean and Median Incomes per municipality in 20017
    <br />
Dataset for visualization of the Swiss map:
    <br />
    <br />
    - Swiss cantonal topojson json file
    <br />
    - Swiss communal geojson
<br />
<br />
All the mentioned data sets were acquired from opendata.swiss or the website of the Swiss confederation. The expectation is to get a sense of different households and get trends on the size of them based on rent price, immigration status and the average income of the area, and analyze discrpeancies between Swiss and foreign residents. The group would like to analyze the households from a social perspective: Has there been a shift in household size in the past years? For instance, the foreign population in the canton of Zurich has increased from 330,000 to 402,000 between 2010 and 2017, an increase of over 70,000. The Lake Geneva region has seen a similar incrase in foreigners during the same period. Are foreigners more likely to live in bigger households and if so, is it because they earn less money or could it be aother reasons? Another example is that between 2010 and 2017, the population living in 1-person household in the city of Zurich decreased from 92,000 to 88,700, while the 3-person household increased from 58,000 to 70,500. While in the city of Winterthur, all households increased between 2010 and 2017. Our group would like to analyze these differences based on social aspects like income levels and immigration status. 
<br />
<br />
The data size would be desireably between 2010 and 2016, based on canton or the 7 big Swiss regions. Meanwhile, when available, we try to focus on a communal resolution. 
<br />

# Contributions of Group Members
<br /> Simon - Extrapolation of Incomes, Correlation Analysis, Heatmap&Scatterplots, Report
<br /> Samuel - Interactive Map, HTML, Exploratory visualization, Data acquisition, Report
<br /> Evgeniy - Data Wrangling, Machine Learning - Prediction, Report

 The poster will be created by the whole group and presented by Simon Stocker
