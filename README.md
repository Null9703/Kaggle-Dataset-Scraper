# Kaggle-Dataset-Scraper

## Purpose
The purpose of this project was to create a web scraping file that collects the most trending datasets on the kaggle website. By default, the project will only show and download those datasets which are a 100 MB in size or less, however this behavior can be altered by changing a single line of code (an if-statement). Additionally, you can change the url in the code and the project will scrape any provided page as long as it has a similar structure to the Kaggle trending page whose URL is already used in the project.

## Technologies
1. Python
2. Kaggle API
3. Requests module
4. BeautifulSoup4
5. Selenium
6. os module
7. json module

## Additional Requirements
Since Kaggle requires a verification of who is currently downloading the datasets, it is required you generate a kaggle.json token file from the official website for use in this project. Just place the file in the same directory as the jupyter notebook. Additional instructions on how to download this file are mentioned in the jupyter notebook.
