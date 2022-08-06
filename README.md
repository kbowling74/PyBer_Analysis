# Pyber Analysis
## <b> Overview </b>
The CEO of ride-sharing company PyBer has requested a summary of ride-sharing data based on city types through a DataFrame and a multiple-line graph. In addition to these items three business recommendations for addressing disparities among the city types were also requested. 

## <b>Resources</b>
<b>Data:</b> city_data.csv <br>
ride_data.csv

<b>Software:</b> Anaconda 2.1.4<br>
Conda 4.12.0<br>
Python 3.9.12<br>
Jupyter Notebook 6.1.12<br>
MatPlotLib 3.5.1<br>
NumPy 1.21.5<br>
Pandas 1.4.2<br>

## <b>Results </b>
The summary DataFrame shows information about fares and drivers based on city types. It was created in Jupyter Notebook using Python and Pandas for data cleaning, merging, and presentation. <br><br>
![PyBer_Summary_DataFrame](https://user-images.githubusercontent.com/106560606/183260281-8321c11c-86c3-4adb-928c-9417e1a3e5e1.png) <br><br>

- Individually the highest earning drivers are in rural areas with an average fare of $55.49 beating the urban driver average fare of $16.57 by nearly 200% and the suburban drivers average fare of $39.50 by roughly 40%. However, the total fares for rural cities being $4,327.93 is only 9% of the total fares for urban cities at $39,854.38. Suburban cities total fares of $19,356.33 are closer at 48% of total urban fares. <br><br>


The multiple-line graph shows information from the summary DataFrame grouped by weeks for the months of January through May. <br>

![PyBer_Summary_Graph](https://user-images.githubusercontent.com/106560606/183262346-4d026c49-9674-4008-a0ec-6fccd4be9817.png) <br>

- The graph clearly shows an increase in rides during the last week of February for all city types followed the next week by a decrease then followed by a slight inscrease. The third week of March also sees a decrease in rides across the board for all cities. 

- This graph also confirms that urban cities are the highest earning out of the three city types with suburban coming in second and rural being the third. 

- Suburban rides peak with the others during the last week of February however they do no peak again to this level as rural and urban rides do later on.

## <b>Summary</b>

The number of urban drivers is higher than the actual ride count for urban rides at 2,405 drivers with only 1,625 rides. This provides an oppurtunity to be able to support up to nearly 800 more rides with the current drivers. At an average fare of $24.53 for urban rides this could be almsot $20,000 is revenue. <br><br>

After the surge of rides in the third week of February a campaign to increase rides for the next week could be helpful. An option to do this would be to provide a discount code that is only valid for the following week could increase the number of rides during that period. <br><br>

Suburban rides during the month of March on average seem to see the largest drop on average compared to urban and rural cities. The peak is reached during the third week fo February and does reach that point again. Advertising or discount codes specifically for suburban riders could increase performance for that city type and get revenue during that month typical to the other city types. 

