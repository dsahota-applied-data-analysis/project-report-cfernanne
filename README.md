This directory includes three functional, self contained google colab notebooks
- Final_Project (Tripartite).ipynb: trains and fits five 3-way classifiers on the full dataset, computes and displays SHAP values for transform model ~ 400 lines of code
- Final_Project (Binary).ipynb:  trains and fits five binary classifiers on the full dataset, ~200 lines of code
- Final_Project (Binary) - Medicine Specific.ipynb: trains and fits five binary classifiers on only the articles topical to healthcare, ~200 lines of code

It further contains the following file, which borrows heavily from QBias' template webscraper of AllSides' headline roundup: https://github.com/irgroup/Qbias/blob/main/README.md

- Final_Project_Scrape.ipynb: template for scraping https://www.allsides.com/headline-roundups using Selenium, as of 2022.
Includes my attempts to update retrieval of links from the table, both via Selenium and BeautifulSoup, without much success. This cannot be run, but was the source of my dataset's retrieval in 2022

And finally, the following datafile:
- all_sides_2022.csv: a selection of AllSides articles (ie, news articles from popular newsmedia across the political spectrum) ranging from 2012-2022,
containing header, category tags, text, source, and bias rating. n = 21,747. 
