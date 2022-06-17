
# Valorant NA Challengers 2 predictions

In this project I predicted the outcome of future games in VALORANT Champions Tour 2022: 
North America Challengers 2 - Group Stage. Had a final prediction rate of 92%

# Project steps 

- Scrape game data using requests, BeautifulSoup, and pandas.
- Clean the data and get it ready for machine learning using pandas.
- Make predictions about who will win a match using scikit-learn.
- Measure error and improve our predictions.

# File overview:

- val na chal2 scraping.ipynb  - a Jupyter notebook that scrapes the data.
- val na chal2 predictions.ipynb - a Jupyter notebook that makes predictions.
- valNA2022stage2matches.csv - csv files of all games from 6/5/2022 to 27/10/20
- valNA2022stage2predictions.csv - predicted outcomes of games during stage 1 and 2 of NA challengers tour


# Local Setup and Installation

To follow this project, please install the following locally:

- JupyerLab
- Python 3.8+
- Python packages
    - pandas
    - requests
    - BeautifulSoup
    - scikit-learn

# Data

Game data scraped from [Liquipedia Valorant](https://liquipedia.net/valorant/VCT/2022/North_America/Stage_2/Challengers/Group_Stage).

# Future

Read data weekly and predict future matches within the 
challengers playoffs and then seed the best teams in NA.
