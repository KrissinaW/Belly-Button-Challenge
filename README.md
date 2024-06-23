# Belly-Button-Challenge
Module 14 

![microbes-sem](https://github.com/KrissinaW/Belly-Button-Challenge/assets/162597320/ee44335b-799d-497b-8858-d981e5f5895a)


# Belly Button Biodiversity Dashboard

## Background

This project involves building an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs) were present in more than 70% of people, while the rest were relatively rare.

## Before You Begin

1. Create a new repository for this project called `belly-button-challenge`. Do not add this challenge to an existing repository.
2. Clone the new repository to your computer.
3. Inside your local git repository, copy the files from the `StarterCode` folder contained within the Module 14 Challenge zip file, i.e., `index.html`, `samples.json`, and the `static` folder.
4. **Note:** You will not be required to access the `samples.json` file locally, but it is provided for reference.
5. Push the above changes to GitHub.
6. Deploy the new repository to GitHub Pages.

## Files

Download the following files to help you get started:

- [Module 14 Challenge files](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json)

## Instructions

Complete the following steps:

1. Use the D3 library to read in `samples.json` from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
    - Use `sample_values` as the values for the bar chart.
    - Use `otu_ids` as the labels for the bar chart.
    - Use `otu_labels` as the hovertext for the chart.

### Bar Chart

3. Create a bubble chart that displays each sample.
    - Use `otu_ids` for the x values.
    - Use `sample_values` for the y values.
    - Use `sample_values` for the marker size.
    - Use `otu_ids` for the marker colors.
    - Use `otu_labels` for the text values.

### Bubble Chart

4. Display the sample's metadata, i.e., an individual's demographic information.
    - Loop through each key-value pair from the metadata JSON object and create a text string.
    - Append an HTML tag with that text to the `#sample-metadata` panel.

### Metadata

5. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard.

## Deployment

Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file.

## Hints

- Use `console.log` inside of your JavaScript code to see what your data looks like at each step.
- Refer to the [Plotly.js documentation](https://plotly.com/javascript/) when building the plots.

## Requirements

### Bar Chart (30 points)

- Chart initializes without error (10 points)
- Chart updates when a new sample is selected (5 points)
- Chart uses Top 10 sample values as values (5 points)
- Chart uses `otu_ids` as the labels (5 points)
- Chart uses `otu_labels` as the tooltip (5 points)

### Bubble Charts (40 points)

- Chart initializes without error (10 points)
- Chart updates when a new sample is selected (5 points)
- Chart uses `otu_ids` for the x values (5 points)
- Chart uses `otu_ids` for marker colors (5 points)
- Chart uses `sample_values` for the y values (5 points)
- Chart uses `sample_values` for the marker size (5 points)
- Chart uses `otu_labels` for text values (5 points)

### Metadata and Deployment (30 points)

- Metadata initializes without error (10 points)
- Metadata updates when a new sample is selected (10 points)
- App Successfully Deployed to Github Pages (10 points)

## Resources

- [D3.js Documentation](https://d3js.org/)
- [Plotly.js Documentation](https://plotly.com/javascript/)
- [GitHub Pages](https://pages.github.com/)
- [ChatGPT](https://openai.com/chatgpt) by OpenAI.




