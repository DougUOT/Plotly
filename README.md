# Plotly
Build an interactive dashboard using Plotly.js to explore data on the biodiversity of belly buttons and then deploy the dashboard to a cloud server.

## Overview of Project

In this module, we will create data visualizations for the web. In order to interact with data, our audience usually needs to have Python installed on their computer. In this module, we will use JavaScript to create data visualizations that are attractive, accessible, and interactive. We will use Plotly, a JavaScript data visualization library. We will also build our JavaScript foundation to manipulate pass and transform data. We will use javascript to create interactive features such as buttons and dropdown menus and retrieve data from external sources like .csv files and API. To the end, we will deploy a polished data visualization to the web.

This assignment is related to the Bootcamp Data Analytics from the University of Toronto and comprises the goals below for this module: 

Follow below the goals for this module:

1) Objective 1: Create a Horizontal Bar Chart
2) Objective 2: Create a Bubble Chart
3) Objective 3: Create a Gauge Chart
4) Objective 4: Customize the Dashboard

## Resources

* Data Source: [index.html](https://github.com/DougUOT/Plotly/blob/main/index.html), also We deployed a sample project to GitHub Pages available on https://douguot.github.io/Plotly/
* Software & Data Tools: Visual Studio Code 1.63.2, Bootstrap 4, Javascript ES6, CSS, HTML and Chrome Browser Version 97.0.4692.71 (Official Build) (64-bit)

## Results & Code

## Objective 1: Create a Horizontal Bar Chart

* Code is written to create the arrays when a sample is selected from the dropdown menu 
* Code is written to create the trace object in the buildCharts() function, and it contains the following: 
    * The y values are the otu_ids in descending order
    * The x values are the sample_values in descending order
    * The hover text is the otu_labels in descending order.
* Code is written to create the layout array in the buildCharts() function that creates a title for the chart 
* When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the bar chart has the following: 
    * The top 10 sample_values are sorted in descending order
    * The top 10 sample_values as values
    * The otu_ids as the labels

![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture_Module12_2.PNG)

![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture_Module12_1_code.PNG)

![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture_Module12_2_code.PNG)

![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture_Module12_3_code.PNG)

## Objective 2: Create a Bubble Chart

* The code for the trace object in the buildCharts(); function does the following:
    * Sets the otu_ids as the x-axis values
    * Sets the sample_values as the y-axis values
    * Sets the otu_labels as the hover-text values
    * Sets the sample_values as the marker size
    * Sets the otu_ids as the marker colors
* The code for the layout in the buildCharts(); function does the following: 
    * Creates a title
    * Creates a label for the x-axis
    * The text for a bubble is shown when hovered over
* When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu 

![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture2_1.PNG)

![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture2_2.PNG)

![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture2_3.PNG)

## Objective 3: Create a Gauge Chart

* The code to build the gauge chart does the following: 
    * Creates a title for the chart.
    * Creates the ranges for the gauge in increments of two, with a different color for each increment.
    * Adds the washing frequency value on the gauge chart.
    * The indicator shows the level for the washing frequency on the gauge.
    * The gauge is added to the dashboard.
    * The gauge fits in the margin of the <div> element.
* When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively, and the gauge chart is working according to the requirements listed for this Deliverable 

![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture3_1.PNG)
  
![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture3_2.PNG)

Using a filter such as 952, see below that the bar, bubble and gauge chart are working correctly, also the dashboard is connected and interactive according as selected by the user.
  
![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture3_3.PNG)

Another filter, for example, using the ID: 962, see below that the bar, bubble and gauge chart are working correctly, also the dashboard is connected and interactive according as selected by the user.
 
![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture3_4.PNG)
  
## Objective 4: Customize the Dashboard

* The webpage has three customizations. 
* When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and all three charts should be working according to the requirements when a sample is selected from the dropdown menu.
  
![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture4_1.PNG)
![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture4_2.PNG)
   
Make the webpage mobile-responsive, the image below showing the dimensions related to the Samsung Galaxy S8+

![](https://github.com/DougUOT/Plotly/blob/main/Resources/Images/Capture4_3.PNG)

## Summary
  
The result of this project is an interactive and connected dashboard with three graphs and filters. This Dashboard was developed for a microbiology laboratory researcher as requested as an objective in this challenge, and it is available on https://douguot.github.io/Plotly/ for public view.

For future improvements to this Dashboard, new features may be added, such as:

* Add more information about the project as a paragraph on the page.
* Add information about what each graph visualizes, either under or next to each graph.
* Add a navigation bar that allows you to select the bar or bubble chart on the page. 
