# Week 3: Scraping Cultural Archives

## Assigned Readings

Continue with:

* [The Science of Culture? Social Computing, Digital Humanities and Cultural Analytics](http://manovich.net/content/04-projects/088-cultural-analytics-social-computing/cultural_analytics_article_final.pdf), Lev Manovich, 2015. 
* [Data Science and Computational Art History](http://manovich.net/content/04-projects/087-data-science/manovich_digital_art_history.pdf), Lev Manovich, 2015.

### Discussion Activities

* Introduction to VROOM display and visual data exploration.

### Homework

* Complete the [Discussion Quiz](https://github.com/roberttwomey/DSC180A-Quantifying-Style/blob/master/02-Cultural_Analytics.md#discussion-questions) on Manovich articles (Due Tuesday 1/28 11:59pm)

For Week 5 Discussion: 
* Please look through the following image processing code examples: [basic-image-stats.ipynb](basic-image-stats.ipynb)
* Use the above code example to create your own notebook
  * Load a single Mondrian image and compute resolution (pixel count), mean saturation, mean brightness.
  * Compute the grayscale variance (Value in the HSV image) for your painting. 
  * Compute the per-rown grayscale variance
  * Approximate an "edge score"
  * Implement all of the above as functions.
* Data Cleaning
  * plot a histogram of resolutions of your scraped images
* Bring your jupyter notebook to class.

### Reference

Recently released online cultural collections:
* [Paris Museums Put 100000 Images online for Unrestricted Public Use](https://kottke.org/20/01/paris-museums-put-100000-images-online-for-unrestricted-public-use?fbclid=IwAR2PvXu2t8tF5c62R9TneZ83KW1klLtr9YjHQz8T7jddY-6AWFxGqlPjs5A)
  * high res images: http://parismuseescollections.paris.fr/en
  * Permissions? (CC0 1.0) https://creativecommons.org/publicdomain/zero/1.0/
* [You Can Now Explore Every MoMA Exhibit Since 1929 for Free Online](https://mymodernmet.com/museum-of-modern-art-exhibition-history/?fbclid=IwAR3LkAPAXmDJ4C9zJn6ujfmhh2zNp6GJL9ysHTMgoKPS5ARp8jx3EklaIUk)
  * MOMA exhibitions: https://www.moma.org/calendar/exhibitions/history?_ga=1.80004629.342658158.1474529993en 
* [San Diego Museum of Art](https://www.sdmart.org/collections/)
  * API?