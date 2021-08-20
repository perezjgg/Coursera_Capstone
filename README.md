# Coursera_Capstone
FINDING THE RIGHT NEIGHBORHOOD TO OPEN A NEW BANK IN ETOBICOKE
José G. Pérez
August, 2021

### 1.	Introduction

  1.1.	Business understanding
An investor is interested in opening a new Bank in the city of Etobicoke, Toronto. This city is the fourth with the most neighborhoods, with 153.794 inhabitants and an average income per inhabitant of $40.935 [1] The investor asked his new business department through his team of Data Scientists an analysis that allows generating recommendations of which is the ideal neighborhood to open to the new Bank based on three considerations: 1) Less competition 2) Greater amount of new clients, 3) Potential clients with better income. From these preliminary variables, the neighborhood where the new bank headquarters will be opened must be identified.

  1.2.	Analytic approach
To select the ideal neighborhood to open the new Bank, we will do an analysis of the demographic data of the Etobicoke neighborhoods, highlighting the number of population, per capita income and population growth. This will allow us to classify the most attractive neighborhoods considering these variables. From these variables we will use the clustering machine learning algorithm (k-means), prior to the application of the algorithm, the standardization of the variables will be carried out, so that they have the same scale. In this way we will group neighborhoods with common demographic characteristics. In this analysis we will incorporate the information from the most common offices around (2000m) of the Eobicoke neighborhoods, with emphasis on the Bank's offices. In this way, we will build a data set that will provide us with demographic data, information on bank offices and the results of the clustering analysis. We will support these analyzes with bank office location maps around neighborhoods acquired from the Foursquare API service. All the analyzes described above will allow us to recommend the suitable vendor to open a new bank.

  1.3.	Data description
In order to make the necessary recommendations to the investor who is interested in opening a new Bank in the city of Etobicoke, the following data sources were used:
•	Toronto demographics features [1].
•	Principal 100 venues around 2000m of the Etobicoke neighborhoods using the Foursquare API services [2].

### 2.	Methodology
The methodological approach used to find the solution to the problem posed was based on the procedure proposed in the course: Data Science Methodology [3].

### 3.	Reference
[1] Toronto demographics (https://en.wikipedia.org/wiki/Demographics_of_Toronto_neighbourhoods).

[2] Foursquare API services (https://es.foursquare.com/developers/apps)

[3] Data science methodology (https://www.coursera.org/learn/data-science-methodology/home/welcome)

