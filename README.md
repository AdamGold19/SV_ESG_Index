# Semantic Visions ESG Index Project Repository

## Overview

This repository contains the code and outputs from the ESG Index project undertaken during my summer internship with Semantic Visions (SV). The project focuses on Environmental, Social, and Governance (ESG) scoring for various companies using proprietary data from Semantic Visions.

## Project Files

### Jupyter Notebook Files

1. **ESGIndexElastic.ipynb**
   - This Jupyter Notebook contains code that calculates ESG scores for selected companies using proprietary data from Semantic Visions via Elastic. Here's a breakdown of what the code does:
     - Converts a CSV file with ESG data for all SV companies into a workable data frame.
     - Cleans the data frame by applying company and ESG relevance thresholds.
     - Iterates through the data frame to match the company name with the input company and retrieve relevant data.
     - Quantifies the collected data to calculate an ESG score based on a predefined equation.
     - Visualizes the ESG scores using matplotlib, displaying color-coded circles that represent the scores and lines connecting them in a tree formation to show category hierarchy.

2. **ESGIndexBigQuery.ipynb**
   - This Jupyter Notebook is an enhanced version of the previous one and calculates company ESG scores using proprietary data from Semantic Visions via Big Query. It includes the following features:
     - A function-based approach, making it user-friendly by allowing users to input a company of choice.
     - Generates a list of items, including overall ESG scores, scores for each ESG category, subcategory, and sub-subcategory, bubble plots for all scores, and trend graphs for scores.
     - Code sections are clearly labeled using markdown for easy navigation.
    
### ESG Visuals

This directory contains visual outputs generated during the testing phase of our ESG scoring system using proprietary data from Semantic Visions. While the data itself is private and not accessible to the public, these visualizations provide insights into the ESG scores for various companies.

### Final Presentation

We have included the final presentation that our team presented to Semantic Visions. This presentation showcases our work and provides an overview of the project's objectives and outcomes.

## Getting Started

Please note that the data used in this project is proprietary to Semantic Visions and not publicly accessible. While you can explore the code and visualizations in this repository, access to the underlying data is restricted to Semantic Visions.

To explore or replicate the code and visualizations, you can follow these steps:

1. Clone this repository to your local machine using the following command:

git clone https://github.com/AdamGold19/SV_ESG_Index.git


2. Open and run the Jupyter Notebook files (ESGIndexElastic.ipynb and ESGIndexBigQuery.ipynb) using Jupyter Notebook or a compatible environment.

3. Explore the ESG visualizations in the "ESG Visuals" directory to gain insights into the ESG scores for various companies.

4. Review the final presentation to get an overview of the project's objectives and outcomes.

## Contributing

Contributions to this project are welcome; however, please note that access to the proprietary data used in this project is restricted to Semantic Visions.

## License

This project is licensed under the [MIT License](LICENSE).

Thank you for exploring my ESG Index project repository. Enjoy exploring the code and visualizations!
