# Mission-to-Mars
In this project data about Mars was scraped from various websites to populate data on a web app created. Data was scraped Using Python and a number of libraries, then stored into a MongoDB database. The scraping function is embedded on the website and pulls live data when the user calls the function by clicking the button. After the data is scraped and in the MongoDB database, a template engine renders the page with the data pulled from the scrape.

## Overview
The challenge for this project was to add to the existing scraping app. First, code was written to extract the title and image url of each hemisphere from the url provided to us. 
![urls and titles](/Resources/urls.PNG)

The code was added as a function to our existing scraping script. After the function was created it was added to the existing scrape all function, so all of the scraping data could be called with one function.
![scrape all](/Resources/scrape_all.PNG)

## Results
The data was successfully scraped and displayed in the app. After the new data was added bootstrap components were used to make the app mobile responsive, along with some other stylings. 
![responsive](/Resources/responsive.PNG) ![responsive2](/Resources/responsive2.PNG)