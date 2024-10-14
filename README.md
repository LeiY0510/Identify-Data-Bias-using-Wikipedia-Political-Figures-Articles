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

Reflecting on this analysis, I was surprised to observe the extent to which certain small countries dominated the per capita rankings. It raises interesting questions about the impact of local community engagement and the potential influence of individual contributors on Wikipedia content. Biases are likely to exist based on where contributors live, their interests, and their access to resources, and addressing these biases could lead to a more equitable distribution of information.

****Reflections on the Assignment****

Before starting this assignment, I expected to find biases in the data, especially towards countries with higher digital literacy and internet accessibility. Countries with more resources and an active internet community were likely to be overrepresented in terms of Wikipedia articles per capita.

During the analysis, I discovered potential sources of bias. These biases are evident in the high representation of certain small countries and low-quality coverage in regions like East and South Asia. The results suggest that Wikipedia, as a data source, reflects the uneven distribution of internet access and content creation capabilities. It is influenced heavily by contributor availability and interest, which can result in overrepresentation or underrepresentation of certain regions. These findings also imply that global society's access to information is skewed based on who has the time, resources, and knowledge to contribute. This can create biases that may misinform users about the actual state of a region's history, culture, or current events.

Using this data for training a model or performing hypothesis-driven research could create biased outcomes due to inherent data gaps. For example, using Wikipedia data to train a model to understand global cultural topics could result in a model that disproportionately reflects the perspectives of highly active contributor regions, ignoring others. However, despite its biases, Wikipedia data can still be useful for understanding the presence and popularity of topics among digitally active populations. Researchers should supplement this dataset with more controlled or balanced datasets, such as official statistics or regional datasets, to correct for observed biases.
