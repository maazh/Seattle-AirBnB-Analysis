# Seattle AirBnB Analysis 

Link to Medium Article: https://medium.com/@maazhassan2/a-quick-guide-to-being-a-successful-airbnb-host-in-seattle-c629dea0d7b4?postPublishedType=initial

#### This repository includes:

    - Seattle_AirBnB_Analysis.ipynb: Which is the source code for the Data Analysis performed and iteratively shows the CRISP - DM process followed to gain insights of the dataset.
    - Seattle_AirBnB_Analysis.html: A web document which viewed via any web browser. 

####  Libraries used:

    - Numpy
    - Pandas
    - Seaborn
    - matplotlib
    - datetime

All of these libraries are part of the Anaconda enviroment and no additional installation is required. Jupyter Notebook was used for data analysis. 

#### Motivation:

This project is part of the Udacity Data Scientist Nanodegree program. The dataset was obtained from AirBnBs website which includes data about the airBnBs in the Seattle region. 

The motivation of this projects stems from a perspective of a potentional host who wishes to rent out his accomdation for AirBnB. The host wishes to know what are the essential requirments that he needs to know in order to be successful and what other characterstics determine tbe success of the AirBnB resulting in a high rating and a good revenue. 

Therefore the fundumtial questions that the host wishes to know and the insights that we draw in this analysis revolve around these three questions:

    1. Which amenities are the most important and play a role in obtaining a high rating therefore increasing revenue. Is there any correlation between one amenity and the other, if so how strong? 

    2. What are the general characterstics of AirBnBs and their hosts with a higher rating. 

    3. How do the prices and the number of bookings fluctuate with regards to time. What are the trends observed within the airBnBs of the three different categories. 

#### Results

The results of the analysis are immensely insightful. They reveal that correlation between various amenities and therefore suggest that if a particular amenity is being offered, what the other important amenities that need to be offered. For example if a Washer is offered, then a dryer ought to be offered as well. Simiarly if either one of these amenities - Air dryer, hanger, Iron ought to be offered too. 

The data reveals interesting stastics about the neighbourhoods and which were the most preffered ones(namely Capital Hill) and what are the various characterstis of high rated hosts which set them apart from other hosts. A time series analysis has also shown which months are crucial and offer a high rate of returns and how the prices various throughout the years. 


#### Acknowledgments:

I would like to thank AirBnB for allowing us to use their data set as well as Udacity for providing me with an opportunity to learn and equip myself with the relavent skill set to perform this analysis task. 

Some necceassary code were used from the following stackoverflow question:
https://stackoverflow.com/questions/17778394/list-highest-correlation-pairs-from-a-large-correlation-matrix-in-pandas

They helped us in the data analysis task and to find correlations between various features. 


