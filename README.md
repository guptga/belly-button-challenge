# Belly-button-challenge

![image](https://user-images.githubusercontent.com/116124534/218005360-c86046a1-0183-45a2-a834-22067682bc39.png)

### Deployment

Here is the screenshot of working Dashboard: 

![image](https://user-images.githubusercontent.com/116124534/218024419-0762fc7b-ea25-4d6e-a8df-a9d0b58ebcf2.png)

### Background

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

### Instructions

Complete the following steps:

1) Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2) Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

3) Use sample_values as the values for the bar chart.

4) Use otu_ids as the labels for the bar chart.

5) Use otu_labels as the hovertext for the chart.

![image](https://user-images.githubusercontent.com/116124534/218010820-6ce15d52-6388-4b29-a3f5-003813f63eab.png)


6) Create a bubble chart that displays each sample.

![image](https://user-images.githubusercontent.com/116124534/218010919-7fecf25f-ef32-4971-914b-806334702f06.png)


7) Display the sample metadata, i.e., an individual's demographic information.

![image](https://user-images.githubusercontent.com/116124534/218010971-c9ae5709-6521-447f-9603-dfe0d8598462.png)


8) Display each key-value pair from the metadata JSON object somewhere on the page.

9) Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard.

10) Deploy your app to a free static page hosting service, such as GitHub Pages.

### Advanced Challenge Assignment

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.

You will need to modify the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.

![image](https://user-images.githubusercontent.com/116124534/218011059-0d8224a7-39b3-4a2f-b5ee-4186d69bb85e.png)



