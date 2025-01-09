# Belly_button_Challenge
The Belly Button Biodiversity Dashboard effectively combines aesthetics, interactivity, and functionality to create a meaningful tool for exploring microbiome data. It demonstrates how modern web technologies can transform complex datasets into accessible and insightful visualizations. With its engaging design and potential for further enhancements, the dashboard represents a significant achievement in science communication and data visualization.

![image](https://github.com/user-attachments/assets/02652a58-95a8-40ae-9d8d-2e2ba869fbf4)

**Project Overview:** The goal of this project was to build an interactive dashboard that visualizes the Belly Button Biodiversity dataset. This dataset catalogs the microbial species found in human navels and aims to explore the distribution of various microbial species (OTUs) across a diverse group of individuals.

Key Objectives and Tasks:

**Data Loading and Setup:**

The samples.json file was accessed using the D3 library, pulling the data required to build the dashboard. The dataset contains details about individual samples, including microbial species IDs, sample values, and demographic metadata.

**Horizontal Bar Chart:**
A horizontal bar chart was created that displays the top 10 OTUs found in the selected individual.

**Key Features:**
The bar chart uses sample_values as the values.
otu_ids are displayed as the labels for the chart.
otu_labels are shown as hover text for additional details.
The chart dynamically updates when a new sample is selected from the dropdown menu.

**Bubble Chart:**

A bubble chart was developed to represent each sample.
Key Features:
otu_ids are mapped to the x-axis.
sample_values are used for both the y-axis and marker size.
otu_ids are also used to color the markers.
otu_labels are displayed as text for each marker.
The chart is interactive and updates according to the selected sample.

**Metadata Display:**

The demographic information associated with each sample was extracted from the metadata JSON and displayed.
The metadata includes key-value pairs like age, gender, ethnicity, etc.
This information updates dynamically when a new sample is selected.

**App Deployment:**

The dashboard was successfully deployed to GitHub Pages, making it accessible online.
The app included a smooth user experience, with the data visualizations and metadata updating seamlessly when selecting a new sample.
GitHub Repository:

The project was regularly committed and updated in a GitHub repository.
A detailed README.md file was included, explaining the project setup, structure, and functionality.

**Outcome:**

The app met all project requirements, including the proper initialization and dynamic updating of the bar chart, bubble chart, and metadata display.
The app was successfully deployed to GitHub Pages and was accessible for public use.
The project was structured to allow for easy exploration of the dataset, with clear visualizations of microbial distributions and personal metadata, providing insights into the microbial biodiversity of human navels.
The project demonstrated proficiency in data visualization, JavaScript (D3.js), and interactive dashboard development, as well as the ability to deploy a fully functional web application.








