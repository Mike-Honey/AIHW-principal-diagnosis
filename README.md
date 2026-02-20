# AIHW-principal-diagnosis

## DataViz project to analyse: Australian Institute of Health and Welfare (AIHW) - Principal Diagnosis for Hospital Separations (patient discharges).

My analysis integrates the data presented by [AIHW as hospital separation datacubes](https://www.aihw.gov.au/reports/hospitals/principal-diagnosis-data-cubes), from the year ending June 2011 onwards.

The data is shared as Excel files with a few variations in the format. My data pipeline attempts to address the most obvious inconsistencies.  Apologies if I introduced any errors during that process.

The data uses a very detailed set of Age Groups - for every 5 year band, up to 84 years old. For quicker analysis, I've added my own Age Group Summary field, which arbitrarily groups sets of AIHW Age Groups.

Note the project's current scope spans multiple editions of the ICD diagnosis definitions, so you may find the codes you are interested in are split under various groups. Where the description changes for a code or group of codes, I present the description from the latest available datacube.


The tool used is [Power BI](https://powerbi.microsoft.com/). This is an interactive data visualisation solution, that allows interactive filtering and exploration of the data, from any modern web browser.  

### Time Series

This page presents the aggregate Separations (patient discharges) by year (each AIHW year ends in June).

As the data is not easily standardisable by population, I have added a series to show how the baseline value would be expected to grow, assuming a population growth rate of 1.5% per annum.


Interactive "slicer" controls at the right of the page allows the user to restrict the Diagnoses shown.  They can also chose Age Groups, and restrict the range of years shown.


[Link to interactive DataViz](https://app.powerbi.com/view?r=eyJrIjoiYjJhNmIxZDAtYTc1ZC00NjE4LWEwNWEtYzA5NzhhYmE1ZmY3IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D)

[![Click to view and interact with the report](https://github.com/Mike-Honey/AIHW-principal-diagnosis/raw/main/AIHW-principal-diagnosis-time-series.png)](https://app.powerbi.com/view?r=eyJrIjoiYjJhNmIxZDAtYTc1ZC00NjE4LWEwNWEtYzA5NzhhYmE1ZmY3IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D)


### Other pages

Several other pages have been created, to explore the % Growth in Separations, and to compare Age Groups. There's a set of "small multiple" pages showing a grid of mini-charts: "By Diagnosis chapter", "By Diagnosis subchapter" etc. 

You can access the other pages using the page navigation control at the bottom, which appears as: **< 1 of 10 >**

## 🤝 Support

Contributions, issues, feature requests and sponsorship are all welcome!

Give a ⭐️ if you like this project!

[![Developed by a Human, not by AI. Click for more info](https://github.com/Mike-Honey/covid-19-au-vaccinations/raw/main/Developed-By-a-Human-Not-By-AI-Badge-white@2x.png)](https://notbyai.fyi)
