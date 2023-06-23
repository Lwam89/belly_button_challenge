# belly_button_challenge

Source Code: The code in this repo uses the base starter code provided. The remaining part of the code reflects individual contributions
Belly-Button Dashboard App Link:file:///C:/Users/lulum/OneDrive/Desktop/DataClass/UCB-VIRT-DATA-PT-01-2023-U-LOLC/02-Homework/14-Interactive-Visualizations/Starter_Code/StarterCode/index.html

Project Background
This assignment asked to build an interactive dashboard using javascript and plotly to explore a dataset which catalogs microbes that live in human belly buttons.

The project consisted of three main components:

Use javascript and d3 to load sample data
Use plotly to visualize data using bar charts, bubble charts and a gauge chart.
Note the gauge chart was not required but was optional for an additional challenge
Use d3 to allow users to select different subjects to analyze and have the graphical items update for each test subject
Use javascript and d3 to load sample data:
Use the D3 library to read in samples.json from the URL
(https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.)
Use d3 selectors to populate the drop down selector menu. Utilize javascript to test source data has been loaded correctly and validate results using the console log.
Use Javascript and Plotly to create visualizations for the dashboard:
Requested Visuals -- to display for a specific test subject ID
Create a drop down (single selection) for individuals to select a test subject ID. Display the sample metadata, i.e., an individual's demographic information. Display each key-value pair associated with the selected test subject
Demographic Panel
Create a horizontal bar chart with the top 10 OTUs found in that individual
Use sample_values as the values for the bar chart.
Use otu_ids as the labels for the bar chart.
Use otu_labels as the hovertext for the chart.
Horizontal Bar Chart
Create a bubble chart that displays each sample
Use otu_ids for the x values.
Use sample_values for the y values.
Use sample_values for the marker size.
Use otu_ids for the marker colors.
Use otu_labels for the text values.
Bubble Chart
BONUS - Create Gauge chart to plot the weekly washing frequency of an individual
Modify the gauge code from Plotly, to account for values ranging from 0-9
Update the chart whenever a new sample is selected
Bonus: Gauge Chart

** Note - Bonus Gauge Chart: The code for the gauge chart is part of the app.js file **
Use javascript and d3 to capture user selection changes:
The dashboard should be configured such that users can select which test subject they wish to view results for
Use d3 to create an event handler to update all visuals whenever a new test subject ID is selected from the dropdown
The dashboard should initialize with the first test subject ID # (940)
