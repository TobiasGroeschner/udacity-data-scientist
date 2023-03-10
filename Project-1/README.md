# Udacity Data Scientist Project 1: Writing a Data Scientist Blog Post

## Necessary packages:

- pandas as pd
- yfinance
- time
- seaborn as sb
- matplotlib.pyplot 

## Project Motivation:

The goal of this project is to fetch information of all DAX30 companies via yfinance. We want to perform simple analysis on the dataset.

## File Descriptions:
- data_scientist_blog_post.ipynb: Notebook where all fetching and analysis has been done 
- 2022-09-26-DAX.xlsx: export of the DAX data
- .png files: pictures for the blog post


## How to interact with this project?

- clone the project `git clone https://github.com/TobiasGroeschner/udacity-data-scientist.git`

The most annoying part of yfinance is to fetch the data and store it in a proper dataframe. Since I have done it in this project, feel free to use the code and do more 
sophisticated analysis with the data.

## Results: 
- The share with the biggest loss was Zalando SE being -78% away from its all time high. That share flew high during Corona but the higher you fly, the more painful the landing.
- The best shares in the DAX were Linde SE and Deutsche Boerese AG. Linde invested in Hydrogen very early on and now has had a headstart as the technology becomes more and more relevant.
- The biggest influence on the 52WeekChange had ebitdaMargins & profitMargins.

Blog article: https://medium.com/@tobias.groeschner/how-to-fetch-data-from-yfinance-and-store-it-in-a-dataframe-775ebe37db6d

## Acknowledgements:
- WIKIPEDIA - The definition of most financial terms were taken from there
- yfinance - thank you for this nice and free module