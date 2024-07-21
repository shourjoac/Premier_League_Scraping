# PremFun

In this project, we will predict the winner of football matches in the English Premier League (EPL) by using data to extract meaning from recent trends.

**Enlisting the steps which helped me conceptualize and implement the project:**

-   Scrape match data using requests, BeautifulSoup, and pandas.
-   Clean the data and get it ready for machine learning using pandas.
-   Make predictions about who will win a match using scikit-learn.
-   Measure error and improve our predictions.

## Code

File overview:

-   `scraping.ipynb`  - a Jupyter notebook that scrapes our data.
-   `predictions.ipynb`  - a Jupyter notebook that makes predictions.

# Local Setup

## Installation

To follow this project, please install the following locally:

-   JupyterLab (or one can use Google Colab)
-   Python 3.8+
-   Python packages
    -   pandas
    -   requests
    -   BeautifulSoup
    -   scikit-learn

## Data


We'll be scraping  [FBref](https://fbref.com/en/)  to get our data in the first part of this project (`scraping.ipynb`).

If you only want to do the second part of the project (`predictions.ipynb`) you can download my `matches.csv`  from above.
