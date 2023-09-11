# Top_10_Texas_EV

### Objective
Conduct a competitor analysis for EV in the state of Texas to review market share and find the trend of EV adoption in Texas cities.

### Resources
The dataset comes from the Texas Vehicle Registration.

### Limitations
Some of the limitations from this dataset includes the lack of MSRP and Range per vehicle. To get an estimate of what the data would look like today, I added the MSRP and Range for every vehicles 2023 model. This means that the revenue doesn't reflect an actual amount but rather an estimate.

### Analysis
During my initial analysis I used pandas in Jupyter notebook to take the dataset and view the different data types and checked for null values. Once columns were checked and approved, I continued to eliminate all rows in which vehicles were not fully a Battery Electric Vehicle by deleting all Hybrid models. Once the Models were all confirmed EVs, I created a frequency table to depict the top 10 EV models in Texas. Finally, I finished the data preparation by adding an MSRP and Range column to depict the 2023 attributes of each model.

Once the data was downloaded and uploaded to Tableau. I proceeded to create sheets and dashboards to represent the different popular makes of EVs in Texas. I did this by showing overall revenue, registered cars, average range of vehicles, and visualizations to show the EV adoption trend in Texas from 2018 - 2022 along with geographic data.

![image](https://github.com/Jaazield4/Top_10_Texas_EV/assets/85451089/977cad6a-5fe2-49ec-a0c7-85e7791e3529)

### Results

#### Highest Ranking EV Make.
Tesla has dominated the EV industry in Texas making for 80% of the total Electric Vehicles registered in the state of Texas. Out of the Top 10 EV Models, 4 of them belong to Tesla. They are the Model 3, Model Y, Model X, and Model S. Because of their high volume, Tesla holds an even market share across Texas and performing highly in urban cities such as Houston, San Antonio, Austin, and Dallas. Over the years Tesla seems to perform better in the third and fourth quarte of the year while their lowest quarter has consistently been the first quarter from 2018 to 2022. 

![image](https://github.com/Jaazield4/Top_10_Texas_EV/assets/85451089/916ac611-ec39-4f51-8975-2955f78bb5fb)     ![image](https://github.com/Jaazield4/Top_10_Texas_EV/assets/85451089/39f290f3-cd55-4a8b-ba76-24bfd5cff06d)


#### Loswest Ranking EV Make
Porsche ranks the lowest in the Top 10 Models with only 3,505 cars registered from 2018 to 2022 making for 1% of the market share in Texas. The only model that Porsche owns in the Top 10 is the Taycan which is considered a luxury car with a base MSRP of $86,700 in 2023 making it the second most expensive vehichle on this list only second to the TESLA Model X. From the map we can see that this type of model only performs well in Urban cities.
![image](https://github.com/Jaazield4/Top_10_Texas_EV/assets/85451089/21c2ba96-0f3c-4402-9819-2d936f529c6c)   ![image](https://github.com/Jaazield4/Top_10_Texas_EV/assets/85451089/dde01ac2-a311-41ce-b49d-7b42e4bf9c52)

