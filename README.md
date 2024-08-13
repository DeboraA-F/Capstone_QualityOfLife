# Capstone_QualityOfLife

#Quality of Life


## Table of Contents
### PowerBi Dashboard
### Motivation
### Questions
### Sources
### The Process
### Technologies Used
### Conclusion


## PowerBI Dashboard
Link:


## Motivation:
I have had the privilege to travel to Ghana, Antigua and Japan and have had pleasant experiences at each one. 
Due to curiosity I wanted to take a look at the average quality of life respective to each country and compare them using my hometown, Columbia, Maryland as a control.
Quality of life is subjective so I defined my parameters by costs of living, health care, crime and pollution 
With this we'll take a look at each country, not from a tourist standpoint, but as a local and if they may be "happy" within these quality of life parameters. In other words I have been happy and content living in my home city, would I feel the same living in another as a local and not as a tourist?
The happiness ranking is drawn from another source to compare our findings with the ranking to see if they match.

**All data is collected from respondents and not from government sources**


## Questions
1.	Comparing and contrasting the countries I have visited (Ghana, Antigua, Japan) with a ‘control’ my hometown 
2.	What are the significant measures to quality of life?
    * Crime rates/safety
    * Health care
    * Pollution/cleanliness
    * Costs of living
3.	Taking a deeper look
    * Breaking down each measure by country	
4.  Taking a look using the United Nations Sustainable Development interpretation of 'happiness' and its components to see if it matches
    with the measures used


## Sources:
[QOL Ghana](https://www.numbeo.com/quality-of-life/in/Accra)

[QOL Japan](https://www.numbeo.com/quality-of-life/country_result.jsp?country=Japan)

[QOL Antigua](https://www.numbeo.com/quality-of-life/country_result.jsp?country=Antigua+And+Barbuda)

[QOL Columbia](https://www.numbeo.com/quality-of-life/in/Columbia-MD)

[World Happiness Report](https://www.kaggle.com/datasets/shivkumarganesh/world-happiness-report-20152022?resource=download)

[United Nations Sustainable Development](https://worldhappiness.report/data/)


## The Process
After finding my sources I web scraped the quality of life and its parameters for each respective country/city using python. I then built dataframes and exported them to PowerBI. Using PowerBI, I cleaned the data and created subsets of dataframes to present as visuals.


## Technologies Used
Python/beautiful soup/pandas - for web scraping, normalizing and creating of the dataframes

powerbi - for cleaning dataframes, creating subsets, and creating an interactive dashboard

git - for version control


## Conclusion
Although I thouroughly enjoyed my various experiences in each country, Columbia, for me, remains the best place for me. As I travel I will expand my dashboard and maybe then, my opinion may change.