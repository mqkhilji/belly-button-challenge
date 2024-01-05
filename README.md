Live demo: https://mqkhilji.github.io/belly-button-challenge/


# Belly Button Biodiversity Dashboard

## Overview

In this project, I have built an interactive dashboard to explore and visualize the Belly Button Biodiversity dataset, which catalogs the microbes inhabiting human navels. This fascinating dataset uncovers that a small group of microbial species, known as operational taxonomic units (OTUs), are prevalent in more than 70% of people, while others are comparatively uncommon.

## Objectives

My objectives in this analysis were to:

1.  Use the D3 library to read in `samples.json` directly from the provided URL.
    
2.  Develop a horizontal bar chart with a dropdown menu to showcase the top 10 OTUs found in a selected individual.
    
3.  Apply `sample_values` as the values for the bar chart.
    
4.  Utilize `otu_ids` as the labels for the bar chart.
    
5.  Employ `otu_labels` as the hover-text for the bar chart.
    
6.  Create a bubble chart that represents each sample.
    
7.  Implement `otu_ids` for the x-axis values.
    
8.  Use `sample_values` for the y-axis values and the marker sizes.
    
9.  Use `otu_ids` to determine the marker colors.
    
10.  Insert `otu_labels` for the text values of the bubbles.
    
11.  Display the selected individual's demographic information, showing each key-value pair from the metadata JSON object.
    
12.  Ensure all plots are updated dynamically when a new sample is selected from the dropdown.
    

## Deployment

The dashboard is fully interactive and has been deployed, offering a user-friendly platform for exploring the diverse ecosystem of microbes found in the human belly button.
