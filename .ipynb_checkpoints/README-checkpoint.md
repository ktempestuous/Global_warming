Aim: show correlation of rise in CO2 emissions and increase in global surface temperature. 

Tableau dashboard: https://public.tableau.com/app/profile/kirsten.tempest/viz/Book1_17398982467110/Changingtemperatures#1

Datasets from Kaggle: 
- CO2: https://www.kaggle.com/datasets/samithsachidanandan/average-monthly-surface-temperature-1940-2024
- 2m surface temperature: https://www.kaggle.com/datasets/ucsandiego/carbon-dioxide

1) Data exploration with python pandas. Tidied and sorted data to create csv files to be imported into Tableau.
2) Data visualisation with Tableau.
- Dashboard shows: 
- top) world map showing difference in yearly averaged temperature between year selected on slider, and 1940.
- bottom) selected yearly range of termperature averaged over countries selected. Dual axis with CO2 concentration in atmosphere. Pearson correlation calculated, updated for data selected. 

Takeaways: 
- Clear positive correlation between rising surface temperatures and CO2 concentrations in atmosphere. When all countries averaged, correlation is 0.93 for the range 1958-2017. Rate of warming not linear however. If look at June temperatures averaged across all countries, clear acceleration in rising temperatures after 1980. 
- All countries are seeing increasing temperatures. Although the rate of warming has not been the same for all countries, by year 2017 all but three countries have had warmer years on average than that of 1940. Note however, that in 2013 these three countries saw warmings in comparison to 1940.

Considerations: 
- Country averages of surface temperature. As country size varies vastly, the standard deviation of temperature in a country can vary vastly between e.g. USA and Liechtenstein.
- Events such as El Niño & La Niña, as well as land composition of a country allow for different feedback effects that will create variability in the rate of warming between countries

Improvements to do: 
- Calculate dynamic max and min temperature difference on world map. Vary colour scale based on this.
- Selecting one county on the map automatically filters for country on line plot below. 
