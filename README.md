# Finding the Most Important Countries of the 20th Century 
<p align="center">
  <img width="614" alt="Screenshot 2024-07-20 at 2 31 08 PM" src="https://github.com/user-attachments/assets/4a4f139f-9c70-4a29-a62f-c972f58f9fa7">
</p>
<h3 align="center">
  Scraping a Wikipedia page to find country interrelations in the 20th century.
</h3>

## CONTEXT
The Institute of Public Policy believes that past events heavily influence the current geopolitical climate. To delve deeper into this hypothesis, a clearer understanding of the historical relationships between countries in the twentieth century is needed. In this case, a visualization of the historical relationships between countries will satisfy that question.

## KEY QUESTIONS
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


## INSTALLATION

## DATA
Founded in 2008, The Movie Database (TMDB) is a comprehensive collection of 1,000,000+ movies including information about the movies' title, genre, ratings, release date, budget, etc. Data is sourced from website members around the world. However, this opens the dataset up to bias and error. The majority of time spent on any analysis with this data should be on cleaning the dataset

**Common issues with the data:**
* films had too much missing data
* tv shows and short films (<40min) were listed in the same category as feature films
* budget and revenue information does not require any proof upon reporting
* there is no standardization on how production companies are listed
* the popularity metric is biased towards recent releases
* TMDB was founded in 2008, so there are many films from before this time that are not included

The full details of the data are available **[here](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies)**





## CONTENTS
1. Project Management
     * Project Brief
2. Data: _Data is not uploaded due to their large size_
     * Original Data
     * Prepared Data
3. Scripts: Jupyter notebooks containing all code
     * Cleaning the Dataset
     * Expanding Variables
     * Exploring Relationships
     * Geographical Visualizations
     * Sourcing & Analyzing Time Series Data
     * Supervised Machine Learning
     * Unsupervised Machine Learning
4. Analysis: Data Profile Report





## TABLEAU STORYBOARD
[Predicting film success using The Movie Database](https://public.tableau.com/app/profile/mattscottjones/viz/JamboreeProductionsAnalysis/Story1?publish=yes)
<p align="center">
<img width=75% alt="Screenshot 2024-07-27 at 5 43 33 PM" src="https://github.com/user-attachments/assets/422b5059-28fd-4170-9784-8f254531d1b0">
</p>


## CITATION
Asaniczka, and themoviedb.org. (2024). Full TMDB Movies Dataset 2024 (1M Movies) [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/9046273
