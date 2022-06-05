# Minds

## Running instructions:
1. Download Chrome Driver with the corresponding Chrome version from https://chromedriver.chromium.org/downloads
2. Replace the path name with the location of the downloaded chrome driver 
`driver = webdriver.Chrome('PATH')`
3. install all the required packages
`pip install -r requirements.txt`
4. run the jupyter notebook

## Total running time:
20s

## Code doc
There are four parts of the code
1. News Scraper: scrapes the most recent 10 news from the website
2. Pre-process: cleans the text and make the text ready to be input into the model
3. Sentiment-analysis: this part uses TextBlob library to output the score of the sentiment
4. Plot: plots the data with a line graph