# Eniac-s-Strategic-Discounting-Analysis
This project involves assessing various aspects related to discounts, product categorization, and their impact on sales and revenue.

## Executive Summary
The company is facing a dilemma regarding the implementation of discounts. While the Marketing Team Lead advocates for discounts, emphasizing their potential benefits in customer acquisition and satisfaction, the main investors are concerned about the impact of aggressive discounts on overall revenue and market positioning.

## Overview
This project was completed as part of a Data Analytics course and evaluates whether Eniac, a premium Apple-focused e-commerce company, should continue to offer discounts as a means to boosting their revenue.
The objective was to use data analysis to support a clear business decision based on operational performance, discount analysis, revenue and seasonality.

## Business Problem
To address the concerns and provide insights to the company board, we'll focus on answering the following questions:

1. How should products be classified into different categories to simplify reports and analysis?	
2. What is the distribution of product prices across different categories?   
3. How many products are being discounted, and what is the magnitude of these discounts as a percentage of product 			prices?	
4. How do seasonality and special dates (Christmas, Black Friday) affect sales?	
5. How could data collection be improved?

## Data Pipeline & Integrity
To ensure a reliable "Source of Truth," the raw data underwent a rigorous cleaning and enrichment process:
* Data Merge: Consolidating datasets from Orders, Orderlines, Products, and Brands.
* Quality Checks: Removal of "Ghost SKUs", Filtering for only 'Completed' order states, Duplicate removal, Validating       	"Uncorrupted price" points.
* Enrichment: Categorizing products into Strategic Business Categories for granular analysis.

## Strategic Recommendations
+ Implement Discount Caps: Keep discounts generally below 20% to preserve brand value and maximize revenue.
+ Alternative Promotions: During seasonal sales, instead of deep price cuts, utilize:
  	*Free delivery. 
  	*Bundled accessories for purchases over a certain amount.
+ Tiered Strategies: Maintain stable, mid-range discounting for Smarthome and Peripheral categories.

## Key Learning
Through this project, I developed the ability to:

* Translate business problems into data-driven analysis
* Use Python to extract, transform and load datas. 
* Build visualizations that communicate clear business insights and connect data findings to strategic business decisions     using Seaborn and Matplotlib.

## Tools Used
+ Python,
+ Seaborn,
+ Matplotlib

## Contributors
+ Barbara Dixon 
+ George Girke,
+ Masha Shahbandeh  
+ Suthanthiradevi Seenivasan
