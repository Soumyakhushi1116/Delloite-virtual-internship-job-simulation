# Delloite-virtual-internship-job-simulation
 Analyse the telemetry data collected by Daikibo in a software called Tableau and created a dashboard.

 Here are the procedures of making dashboard:

1. Download the daikibo-telemetry-data.json.zip file -> unzip -> and import it in Tableau.
2. Create a calculated measure field called "Unhealthy" with a value of 10 for every unhealthy status (representing 10 mins of potential down time since the previous message).
3. Create a bar chart called “Down Time per Factory”.
4. Create a new sheet with a new bar chart called “Down Time per Device Type”.
5. Create a Dashboard with the 2 previous sheets and set the first chart to be used as a filter (selecting a factory in the first chart shows only the down time of the machines in this factory in the second chart).

The questions that have been answered using this dashboard are:
1. In which location did machines break the most?
2. What are the machines that broke most often in that location?
