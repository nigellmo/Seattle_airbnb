# Analysis on Seattle_airbnb

# Libraries used in the project
--------------------------------
The project is run under Python 3.0 with utilization of below libraries:
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Datatime
6. Folium
7. warnings
8. Sklearn

# Motivation for the project
--------------------------------
Assume it is to start lodging business in Seattle, there may be a lot of business considerations including profit return, difficulties to lease, seasonal influence, etc. This project may not be able to answer all but provide some insight on general situations in Seattle by answering below questions:

    • Traffic convenience and variety of entertainment are usually very important factors to consider where to start lodging business. Is it the same case in Seattle? 
    • For popular lodging areas, what are the ranges of average leasing prices of lodgings and how is the variation under seasonal factors ?
    • Will it be easy to lease lodging in Seattle?
    • What factors are determining leasing prices of lodgings?
  
# File Descriptions
--------------------------------
Analysis file: 
- Seattle AirBnB v1.1.ipynb: This jupyter notebook runs through CRISP-DM to provide data mining and analysis subject to questions mentioned in :"Motivation for the Project".

Data files: Data set from Kaggle on Seattle AirBNB was chosen for this purpose.(see Acknowledgement)
- listings: data on attributes of lodgings including links, geographic coordinates, charges, rating, etc.
- reviews: comment from AirBnB users on the lodges
- calendar: price and availability information of lodges every day


# Summary of the results of the analysis
--------------------------------
1. Like other popular cities for travel, Density of lodges is the highest with relatively higher leasing prices in the Central Business District, which means traffic convenience and variety of entertainment are also one of the important considerations to start lodging business in Seattle.

2. Seasonal trend for leasing prices were obvious.

3. In general it does not seem to be always a profitable business to run a lodge in Seattle since vancancy rate could be very high in some districts(Neighbourhood). Past data suggested that First Hill may be the district with highest chance to lease.

4. Factors determining leasing price of lodges are more related to size of lodges and facilities like bathrooms and bedrooms, and less related to review attributes(e.g. number of reviews and review rating scores). Because of that in order to provide more accurate prediction using machine learning we shall need more data on size of lodges and facilities.


# Acknowledgement
--------------------------------
Reference of original data: https://www.kaggle.com/airbnb/seattle/data

