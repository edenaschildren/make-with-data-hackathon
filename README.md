<!---# hackathon-make-with-data-->
<h2 align="center">Hackathon for Make-With-Data: Mapping Mental Health Repository</h2>

<p align="center"><img src="https://github.com/edenaschildren/make-with-data/blob/main/images/make-with-data-hackathon-march-2026_banner.png" alt="Make-With-Data_Hackathon_banner" width="400" ></p>

<h3 align="left">Overview</h3>

Make-With-Data supports the research of community-based challenges, primarily related to local conservation, sustainability, and mental health. The workshops are full of activities that align real world challenges with data sources and scientific methods to explore solutions that simultaneously teach important mapping and data science skills.

DNM Geospatial is assisting Edenas Children to obtain a baseline for understanding the state of mental health in NYC and how it correlates with environmental, socioeconomic and demographic variables. 

The “Make-With-Data: Mapping Mental Health” workshop series is culminating with this Hackathon to engage the community to make maps that visualize what we have researched so far. We feel it’s important to not only share this information with the community but to engage them in the skills required to do so.

This Hackathon is intended to get the community to participate in making maps based on data that we found suitable, for the purpose of establishing a baseline understanding of the state of mental health in NYC. 

<h3 align="left">Audience </h3>

<p>The target audience for this hackathon is anyone interested in making maps related to mental health. We invite all curious students, community members, and professionals from across disciplines to participate in this event.</p>

<p>Main takeaways are awareness of mental health data, skills in basic statistics and mapping techniques. </p>

<p>Participants will make-a-map of depression in NYC, which they can share with their community to increase awareness and/or add to their portfolio and increase their visibility and network.</p>


  
<h3 align="left">Theme </h3>
<p>Depression is a mental health condition that has been measured in NYC over the past 20+ years. The data we'll use is publicly available at NYC (citywide), Borough, and Neighborhood geographic levels for the select years between 2017-2022. </p>

<p>We'll present the definition for the depression variables, basic data science techniques to obtain statistics about the data, mapping techniques used for this type of data, and options for how to tell a story using this type of data, then you will use what you know to make-with-the-data.</p>

<p>Let's dive in a see what you can make!</p>


<h3>Timeline and Agenda</h3>

<h4>In-Person Agenda 3/25:</h4>
- 

- 1:15 - 1:30 - Networking
- 1:30 - 1:45 - Welcome and Breathwork Exercise              
- 1:45 - 2:00 - Introductions
- 2:00 - 2:45 - Make-With-Data Workshop 
- 2:45 - 3:00 - BREAK — Q/A 
- 3:00 - 4:30 - Hackathon
- 4:30 - 5:00 - Break -- Q/A -- Light food and refreshments
- 5:00 - 7:00 - Hackathon
- 7:15 - 7:25 - Q/A, Recap and Next Steps
- 7:25 - 7:30 - Closing and Breathwork Exercise
- 7:30 - 7:45 - Networking

<h4> Submit Map 3/26</h4>

<p>Map Submissions are due Thursday March 26th by Midnight 
Use this form to submit your map:   </p> 
 <a href="https://forms.gle/fdiCXiY4S7rq1MXT8" target="_blank" rel="noopener noreferrer">Submit your final make-with-data map! </a>

<h4> Judges will score the maps virtually on Friday March 27th  </h4>

<h4> Winners will be announced on Saturday March 28th </h4>


<h2>Make-With-Data Instructions</h2>

<h3>Software</h3>
<p>While you are free to use any mapping platform that you choose, we will be workshopping with QGIS, a free and open source software. You can prepare by having the software already installed on your system. </p>

<p>Download QGIS for your computer platform here: <a href="https://qgis.org/download/"> https://qgis.org/download/ </a></p>

<h3 align="left">Reference Data Files</h3>

| Name | Data File | 
| --- | --- | 
| NYC Borough Boundaries | [NYC_Borough_Boundaries.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/NYC_Borough_Boundaries.geojson )
| NYC Neighborhood Names | [NYC_Neighborhood_Names.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/NYC_Neighborhood_Names.geojson ) 
| NYC Metropolitan Area Counties | [NYC_Metro_Counties.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/NYC_Metro_Counties.geojson ) 



<h3 align="left">NYC Community Health Survey (CHS) Data</h3>
<p>The original data downloaded from the NYC DOH Environment & Health Data Portal are text files with location information. We joined the text files to NYC Borough Boundaries and United Health Fund (UHF42) Boundaries. UHF are used to represent Neighborhoods. The resulting data files below are map-ready for your use.</p>

<h4>Use this citation on your map: New York City Department of Health, Environment & Health Data Portal. Mental health data. Depression (adults). Accessed at https://a816-dohbesp.nyc.gov/IndicatorPublic/data-explorer/mental-health/?id=2417 </h4>


<h3> Data Dictionary </h3>

<a href="https://docs.google.com/spreadsheets/d/1SrCfiKLkepWn8gITGjPI-WpDCNl1ovNp9nJhaIJYegU/edit?usp=sharing" target="_blank" rel="noopener noreferrer"> Hackathon for Make-With-Data: Mapping Mental Health Data Dictionary </a>

<h3> Data Files to Use</h3>


| Variable | Measure | Year  | Geography | Data File | 
| --- | --- | --- | --- | --- | 
| Depression | Age-adjusted Percent (%) | 2017-2018 | Borough | [CHS_Borough_Depression_Age_adjusted_Percent_2017_2018.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/CHS_Borough_Depression_Age_adjusted_Percent_2017_2018.geojson) 
| Depression | Age-adjusted Percent (%) | 2021-2022 | Borough | [CHS_Borough_Depression_Age_adjusted_Percent_2021_2022.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/CHS_Borough_Depression_Age_adjusted_Percent_2021_2022.geojson)  
| Depression | Percent (%) | 2017-2018 | Borough | [CHS_Borough_Depression_Percent_2017_2018.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/CHS_Borough_Depression_Percent_2017_2018.geojson) 
| Depression | Percent (%) | 2021-2022 | Borough | [CHS_Borough_Depression_Percent_2021_2022.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/CHS_Borough_Depression_Percent_2021_2022.geojson)
| Depression | Age-adjusted Percent (%) | 2017-2018 | Neighborhood | [CHS_UHF42_Depression_Age_adjusted_Percent_2017_2018.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/CHS_Borough_Depression_Age_adjusted_Percent_2017_2018.geojson) 
| Depression | Age-adjusted Percent (%) | 2021-2022 | Neighborhood | [CHS_UHF42_Depression_Age_adjusted_Percent_2021_2022.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/CHS_Borough_Depression_Age_adjusted_Percent_2021_2022.geojson) 
| Depression | Age-adjusted Percent (%) | 2017-2018 | Neighborhood | [CHS_UHF42_Depression_Percent_2017_2018.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/CHS_Borough_Depression_Percent_2017_2018.geojson)
| Depression | Age-adjusted Percent (%) | 2021-2022 | Neighborhood | [CHS_UHF42_Depression_Percent_2017_2018.geojson](https://github.com/edenaschildren/make-with-data/blob/main/data/CHS_Borough_Depression_Percent_2021_2022.geojson)




<h3 align="left"> Map criteria</h3>

<p>Original work! Do not use AI for any part of this process. You can use the Internet for research however making the map must be your own work. </p>

<h4>Map Submissions are due Thursday March 26th by Midnight 
Use this form to submit your map:   </h4> 
 <a href="https://forms.gle/fdiCXiY4S7rq1MXT8" target="_blank" rel="noopener noreferrer">Submit your final make-with-data map! </a>

<h4 >Content 40pts</h4>

- Effective communication / Storytelling -  Is the map’s story clear? Does the content support the map’s intended purpose?

- Effective use of basic statistics 

- Sources – Are sources appropriately credited/cited?

- Disclaimers - Any disclaimers provided in the metadata / data dictionary for the variables used must be included on the map

<h4>Presentation 40pts</h4>

- Visualization, Visual appeal (color coordination, accents, highlights, use of  classification)

- Legibility (font, font size, figures, tables, graphics) – Are fonts, text size, and labels configured in a way that is legible? 

- Design/Layout – Do the graphical elements follow a logical arrangement?
  
- Your map should include standard cartographic elements: title, legend, and major data sources listed.


<h4>Creativity 20 pts</h4>

- Overall impact

- Is there anything unique?

<h3>Prizes</h3>
<p>All participants will receive a digital certificate acknowledging their map entry (upon request). Winning maps will be displayed on the Edenas Children website and social media. </p>
-

- 1st place, $100
- 2nd place, $50
- 3rd place, $25
- 4th place, honey bear
- 5th place, honey bear 
 
  

<h3>Judges</h3>
- 

- Swati Sharma, GIS Specialist, Urban Planner
- Allison Lacko, PhD, Research Scientist, Public Health Nutrition
- Daniel Bader, Climate Scientist
- Jeffrey Rothstein, PhD, Artist and Photographer 
- Neil Mendeloff and Christopher Baptiste, Edenas Children Board of Directors


<h3>Thank you for participating in the March 25th, 2026 <a href="https://edenaschildren.org">Edenas Children</a> Hackathon for Make-With-Data: Mapping Mental Health in partnership with <a href="https://dnmgeospatial.org">DNM Geospatial </a></h3>

<h3>Follow us on Instagram to see the winning maps: <a href="https://www.instagram.com/edenaschildren"> @edenaschildren </a> and <a href="https://www.instagram.com/dnmgeospatial"> @dnmgeospatial </h3>




