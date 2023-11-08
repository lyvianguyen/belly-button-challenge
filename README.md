# Belly Button Challenge
In this assignment, we will create an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset provides insights into the presence of microbial species (OTUs) in the human navel, with some OTUs being common in more than 70% of people and others relatively rare.

## Getting Started
1. Create a New Repository

- Create a new GitHub repository for this project and name it "belly-button-challenge." Do not add this Challenge to an existing repository.

2. Clone the Repository

- Clone the newly created "belly-button-challenge" repository to your local computer.

3. Add Starter Files

- Inside your local git repository, copy the following files from the "StarterCode" folder contained within the provided Module 14 Challenge zip file:
  - index.html
  - samples.json
  - The static folder.

4. Push to GitHub

- Commit and push the above changes to your GitHub repository.

5. Deploy to GitHub Pages

- Deploy your repository to GitHub Pages to make your interactive dashboard accessible to others.

## Instructions
To complete this assignment, follow these steps:

1. Read the JSON Data

- Use the D3 library to read in the samples.json data from the URL: https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2. Create a Horizontal Bar Chart

- Create a horizontal bar chart with a dropdown menu that allows users to select an individual.
- Use the sample_values as the values for the bar chart.
- Use the otu_ids as the labels for the bar chart.
- Use the otu_labels as the hovertext for the chart.

3. Create a Bubble Chart

- Create a bubble chart that displays each sample.
- Use otu_ids for the x values.
- Use sample_values for the y values.
- Use sample_values for the marker size.
- Use otu_ids for the marker colors.
- Use otu_labels for the text values.

4. Display Sample Metadata

- Display the sample metadata, which includes an individual's demographic information.
- Display each key-value pair from the metadata JSON object somewhere on the page.
