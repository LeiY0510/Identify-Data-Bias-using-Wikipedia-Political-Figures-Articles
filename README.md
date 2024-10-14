# Identify-Data-Bias-using-Wikipedia-Political-Figures-Articles
This analysis considered articles on political figures from different countries. It combined a dataset of Wikipedia articles with a dataset of country populations, and use a machine learning service called ORES to estimate the quality of each article.
README

****Project Title****
Identify Data Bias using Wikipedia Political Figures Articles

****Project Description****
The goal of this analysis is to explore the concept of bias in data using Wikipedia articles. This analysis considered articles on political figures from different countries. This analysis combined a dataset of Wikipedia articles with a dataset of country populations, and used a machine learning service called ORES to estimate the quality of each article.

****Table of Contents****
Step 1: Load And Clean Data
Step 2: Article Page Info MediaWiki API
	2.1 Make a page info request to get the current page revision
	2.2 Make an ORES request using the page title and current revision id
Step 3: Combining the Datasets
Step 4: Analysis & Results
	4.1 Top 10 countries by coverage: The 10 countries with the highest total articles per capita (in descending order).
	4.2 Bottom 10 countries by coverage: The 10 countries with the lowest total articles per capita (in ascending order).
	4.3 Top 10 countries by high quality: The 10 countries with the highest high-quality articles per capita (in descending order).
	4.4 Bottom 10 countries by high quality: The 10 countries with the lowest high-quality articles per capita (in ascending order).
	4.5 Geographic regions by total coverage: A rank-ordered list of geographic regions (in descending order) by total articles per capita.
	4.6 Geographic regions by high-quality coverage: Rank ordered list of geographic regions (in descending order) by high-quality articles per capita.

****License****
This code example was developed by Lay(Lei) Yang for use in DATA 512, a course in the UW MS Data Science degree program. Some part of this code is provided under the Creative Commons CC-BY license. Revision 1.0 - August 15, 2023

****Research Implications****
This analysis provided valuable insights into the geographic distribution of articles and the quality of coverage across different regions and countries. The Research Implications of this assignment revolve around understanding the biases that exist in data collection, coverage, and quality assessment when dealing with large-scale, user-generated sources such as Wikipedia. 

****Lessons Learned & Found****
One of the key findings was that certain small countries, such as Monaco and Tuvalu, had disproportionately high articles per capita, which suggests an over-representation in terms of Wikipedia coverage compared to their population size. This may be due to biases in editor interest or the presence of active contributors from those regions. Countries with larger populations might be underrepresented in terms of Wikipedia articles, while smaller or more prominent countries might be overrepresented. The observed biases underline the challenges of relying on user-generated content for broad data coverage in research contexts.

Additionally, we found that regions like South Asia have a relatively lower number of high-quality articles per capita, while certain smaller regions have a higher concentration of quality content. This suggests there may be a quality gap that is influenced by socioeconomic factors, digital literacy, or active Wikipedia contributors in those areas. Understanding these patterns helps in identifying regions that could benefit from targeted initiatives to improve article quality and reduce content disparities.
