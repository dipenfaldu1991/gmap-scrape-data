# Google Maps Scraper
Scraper of Google Maps reviews.
The code allows to extract the **most recent** reviews starting from the url of a specific Point Of Interest (POI) in Google Maps.


## Installation
Follow these steps to use the scraper:
- Download Chromedrive from [here](https://chromedriver.storage.googleapis.com/index.html?path=2.45/).
- Install Python packages from requirements file, either using pip, conda or virtualenv:

generates a csv file containing last 50 reviews of places present in _urls.txt_

In current implementation, the CSV file is handled as an external function, so if you want to change path and/or name of output file, you need to modify that function.


Url must be provided as expected, you can check the example file urls.txt to have an idea of what is a correct url.
If you want to generate the correct url:
1. Go to Google Maps and look for a specific place;
2. Click on the number of reviews in the parenthesis;
3. Save the url that is generated from the latest interaction.

For a basic description of logic and approach about this software development, have a look at the [Medium post](https://towardsdatascience.com/scraping-google-maps-reviews-in-python-2b153c655fc2)
