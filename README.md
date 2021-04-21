# Boston-Airbnb 
Airbnb started off on a simple idea: affordable accommodations for travellers and some side income for homestay providers. After 14 years, this idea has evolved into a mature online business with hundreds of thousands of online bookings every day. The large amount of booking and review data collected behind scene will reveal some patterns or business insights in this billion-dollar marketplace.
A few business questions of interest:
1. How are listings distributed in Boston?
* How do listing price and booking rate change throughout the year?
* What do people value the most about their homestays?
* Can listing price be predicted?

## CSV files
Three csv files used in this notebook
* Listings_boston: contains detailed information about each listing, such as property features, host information, listing descriptions and review scores
* calensar_boston: price and availability of 3,585 property listings during Sep 2016-Sep 2017
* reviews_boston: reviews for 2,829 listings from 2009 to 2016

## Libraries
There are five main libraries used in this analysis. They are Pandas for dataframe transformation, Numpy for data calcuation, matplotlib for visualization, NLTK for natural language process and Sklearn for modelling.

## Results summary
Here are a few main takeways from this analysis:
*	Waterfront neighbourhood holds the highest listing price on average in Boston
*	Listing price fluctuates significantly more throughout the year in some neighbourhoods than in others
*	Location and cleanness of homestay are the most important factors to people. 
*	Listing price can be predicted with this dataset.


## Blog post
You can find my blog post [here](https://medium.com/@dongshimiao/do-you-understand-airbnb-activity-of-homestays-in-boston-d9074193a9a6)

## GitHub repo Link
You can find the detailed python code regarding Boston Aribnb analysis [here](https://github.com/ShimmyD/Boston-Airbnb/blob/master/Boston_Airbnb.ipynb)

## Acknowledgements
* Kaggle
* Udacity
