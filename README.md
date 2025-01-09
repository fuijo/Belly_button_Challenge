# Belly_button_Challenge
The Belly Button Biodiversity Dashboard effectively combines aesthetics, interactivity, and functionality to create a meaningful tool for exploring microbiome data. It demonstrates how modern web technologies can transform complex datasets into accessible and insightful visualizations. With its engaging design and potential for further enhancements, the dashboard represents a significant achievement in science communication and data visualization.

![image](https://github.com/user-attachments/assets/02652a58-95a8-40ae-9d8d-2e2ba869fbf4)


# Instructions
//**Complete the following steps:**

Use the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.

Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

Use sample_values as the values for the bar chart.

Use otu_ids as the labels for the bar chart.

Use otu_labels as the hovertext for the chart.

// **Bar Chart**

Create a bubble chart that displays each sample.

Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.

// **Bubble Chart**

Display the sample's metadata, i.e., an individual's demographic information.

Loop through each key-value pair from the metadata JSON object and create a text string.

Append an html tag with that text to the #sample-metadata panel.

Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

**Hints
Use console.log inside of your JavaScript code to see what your data looks like at each step.

Refer to the Plotly.js documentationLinks to an external site. when building the plots.
