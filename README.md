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
     - Visualizes the ESG scores using matplotlib, displaying color-coded circles representing the scores and lines connecting them in a tree formation to show category hierarchy.

2. **ESGIndexBigQuery.ipynb (the main code)**
   - This Jupyter Notebook is an enhanced version of the previous one and calculates company ESG scores using proprietary data from Semantic Visions via Big Query. It includes the following features:
     - A function-based approach, making it user-friendly by allowing users to input a company of choice.
     - Generates a list of items, including overall ESG scores, scores for each ESG category, subcategory, sub-subcategory, bubble plots for all scores, and trend graphs for scores. (check out ESG Visuals folder)
     - Code sections are clearly labeled using markdown for easy navigation.
    
### ESG Visuals

This directory contains visual outputs generated during the testing phase of our ESG scoring system using proprietary data from Semantic Visions. While the data itself is private and not accessible to the public, these visualizations provide insights into the ESG scores for various companies and how we displayed our findings.

### Final Presentation

I have included the final presentation that my team presented to Semantic Visions. This presentation showcases our work and provides an overview of the project's objectives and outcomes.

## Thank You

Thank you for exploring my ESG Index project repository. Enjoy reviewing the code and visualizations!
