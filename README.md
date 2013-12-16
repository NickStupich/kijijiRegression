kijijiRegression
================
Some pretty basic regresison analysis - figure out if a car is a good deal or not within a certain city from all the kijiji adds

to run things:
pick a 'city' (a city and car combo), and the url to the first listing page for that city and car.  Any filters can be set on that page
things are cached in a new folder for every car and city combo.  If you want freshly scraped data, delete the folder
then 'python extract.py' to extract data and create a tab separated data file
'python analyze.py' to make a plot of the expected vs listing price.  Click on a data point to get the url and check out the car.  Set the data file in the code