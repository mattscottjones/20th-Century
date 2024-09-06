# Finding the Most Important Countries of the 20th Century 
<p align="center">
  <img width="614" alt="Screenshot 2024-07-20 at 2 31 08 PM" src="https://github.com/user-attachments/assets/4a4f139f-9c70-4a29-a62f-c972f58f9fa7">
</p>
<h3 align="center">
  Scraping a Wikipedia page to find country interrelations in the 20th century.
</h3>

## TABLE OF CONTENTS
* General Info
* Tools
* Data Source
* Project File Setup
* Citation


## GENERAL INFO
The Institute of Public Policy believes that past events heavily influence the current geopolitical climate. To delve deeper into this hypothesis, a clearer understanding of the historical relationships between countries in the twentieth century is needed. In this case, a visualization of the historical relationships between countries will satisfy these key questions:

1. Which countries had the most influence during the 20th Century?
2. What patterns in country relationships can we identify?

<p align="center">
<img width=48% alt="Screenshot 2024-07-27 at 10 31 08 AM" src="https://github.com/user-attachments/assets/dbf34d85-3024-4327-9cee-79afd1a51f4e">      <img width=48% alt="Screenshot 2024-07-27 at 5 36 03 PM" src="https://github.com/user-attachments/assets/b28a693b-21f5-44fe-9ce1-71e51d81c5e4">
</p>


## TOOLS
For this project, the following Python libraries were used:
* pandas - for data analysis
* numpy - for mathematical equations
* matplotlib + seaborn - for data visualization
* Selenium + BeautifulSoup - for scraping data
* NLTK - for processing data into tokens
* TextBlob - for part of speech tagging
* spaCy - for named entity recognition
* NetworkX + pyvis - for creating networks and network visualizations
* CDlib - for evaluating the networks


## DATA
Data was scraped from the Wikipedia page, **[Key events of the 20th century](https://en.wikipedia.org/w/index.php?title=Key_events_of_the_20th_century&oldid=1244115362)**, in August 2024. Using BeautifulSoup the full text of the article was saved as a text file. And using Selenium, all names of countries in the article were compiled into a csv file. 

The full details of the data are available **[here](https://en.wikipedia.org/w/index.php?title=Key_events_of_the_20th_century&oldid=1244115362)**.


**Note:** The information on Wikipedia is curated by editors around the world. Although there is little incentive for bias in this data, the method of data recording lends itself to possible errors. Also, relying on only one source to determine a country's global importance introduces sampling bias. Depending on the main contributing editors to this Wikipedia page, there may be an emphasis on certain countries' involvement in global affairs over others. For instance, in 2024, we're seeing the consequences of many decades of unrest between Egypt, Israel, Palestine, Syria, and other Middle Eastern countries. The preceding events, that began in the 20th century, are not mentioned in this article.


## PROJECT FILE SETUP
1. Project Management
     * Project brief laying out the expectations and deliverables
2. Data
     * Wikipedia text file
     * List of countries csv file
     * Cleaned data files for analysis
3. Scripts: Jupyter notebooks containing all code
     * Creating a Virtual Environment
     * Data Scrape
     * Text Mining
     * Data Cleaning
     * NLP Network Analysis
     * Network Visualizations
4. Visualizations
     * Network Visuzlaitions
     * Centrality Measure bar charts
  
<p align="center">
<img width=48% alt="Screenshot 2024-07-27 at 10 31 08 AM" src="https://github.com/user-attachments/assets/dbf34d85-3024-4327-9cee-79afd1a51f4e">      <img width=48% alt="Screenshot 2024-07-27 at 5 36 03 PM" src="https://github.com/user-attachments/assets/b28a693b-21f5-44fe-9ce1-71e51d81c5e4">
</p>




## CITATION
Key events of the 20th century. (2024, September 6). In Wikipedia https://en.wikipedia.org/w/index.php?title=Key_events_of_the_20th_century&oldid=1244115362
