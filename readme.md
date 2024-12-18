## Interactive Visualizations
---

# Belly Button Biodiversity Dashboard

## Table of Contents
- [Description](#description)
- [Data Files](#data-files)
- [Features](#features)
- [Installation](#installation)
- [Results](#results)
- [Author](#author)

---

## Description

This project builds an **interactive dashboard** to explore data from the Belly Button Biodiversity dataset. The dataset includes information on bacterial cultures found in samples taken from human navels. The project visualizes data for individual test subjects, providing insights into bacterial diversity.

The application uses **HTML**, **JavaScript**, and the **D3.js** library to load and process the dataset, and **Plotly.js** to generate interactive charts.

---

## Data Files

| File Name         | Description                                           |
|-------------------|-------------------------------------------------------|
| `index.html`      | Main HTML file that structures the dashboard.         |
| `app.js`          | JavaScript file that handles data loading and charts. |
| `samples.json`    | JSON file containing the dataset.                     |

---

## Features

1. **Metadata Panel**:
   - Displays demographic information for the selected test subject.

2. **Interactive Bar Chart**:
   - Visualizes the **Top 10 OTUs** (Operational Taxonomic Units) for the selected sample.

3. **Bubble Chart**:
   - Shows the distribution of all bacterial cultures (OTUs) by sample values.

4. **Dynamic Dropdown**:
   - Allows users to select a test subject ID and dynamically updates the charts and metadata.

---

## Installation

1. **Prerequisites**:
   - A modern web browser (Chrome, Firefox, Edge, etc.)
   - Internet connection (to access external D3.js and Plotly.js libraries)

2. **Setup**:
   - Clone this repository or download the project files.
---

## Results

### Key Insights:

1.	Top Bacteria Cultures:
   - The most common bacterial cultures differ across test subjects.
2.	Diversity of Bacteria:
   - Bubble charts highlight the richness of bacterial species in the samples.

Example Outputs:
   - Bar Chart: Displays the top 10 bacterial OTUs found in a specific sample.
   - Bubble Chart: Shows bacterial cultures sized by their abundance.