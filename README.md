# Clustering Analysis and Prediction of Housing Pricing Using Deep Learning Algorithm.
 Segementation of housing sales informationa into groups, analyse each group and buld a model to predict the price of homes.
 
 
## Phase 1:  Clustering Analysis on the Housing Data


### Business Problem:

A house flipping company would like to identify underpriced homes by comparing asking prices to predicted sale prices.   They would like to segment homes into groups to analyze what kinds of homes there are. They would also like a model that predicts the selling price of a home.

The company has provided publicly available data from the King County Assessor's office to use for clustering and prediction.

**Data notes:**

BrickStone is the percentage of a house that is made of brick or stone.

### Objectives:

The house flipping company would like you to segment the homes sold in the database and create an analytical report on the clusters describing each cluster and describing how they are different. The data has had some cleaning work to it, but you should verify that it is ready for clustering.

### Actions:
All unneccssary columns were removed. All duplicates were droped and all inconsistency issues were addressed. Kmeans clustering Algorithm was used to cluster data four groups.

![housing clusters](https://user-images.githubusercontent.com/95732821/176503337-cf9c25b2-6ae4-4108-aefd-5182d344c1e8.png)



### Results:


**Cluster 0**

Houses in this cluster have an average of the following:
*   Sales price:            $800,000
*   First floor size:       over 1500 sqft.
*   Half floor size:        about 150sqft.
*   2nd floor size :        less than 10 sqft. 
*   Upper floor:            less than 10 sqft
*   Total living space:     2000 sqft.
*   Basement size:          About 1000 sqft.
*   Finished basement size: 500 sqft.
*   Garage basement:        140 sqft
*   Attached garage:        About 90 sqft
*   Daylight basement:      about 0.3
*   Open porch:             40sqft
*   Enclosed porch:         less than 5 sqft
*   Deck:                   About 100sqft
*   Brickstone:             About 100%
*   Bedrooms:               3
*   Bathhalfcount:          less than 0.4
*   Bath3qtr count:         About 0.5
*   Bathfullcount:          1
*   Year:                   2000.
*   Longitude:              Above 0 
*   Latitude:               50


**Cluster 1**

Houses in this cluster have an average of the following:
*   Sales price:            $700,000
*   First floor size:       About 500 sqft.
*   Half floor size:        less than 10sqft.
*   2nd floor size :        About 500 sqft. 
*   Upper floor:            About 140 sqft
*   Total living space:     About 1500sqft.
*   Basement size:          about 400 sqft.
*   Finished basement size: 250 sqft.
*   Garage basement:        100 sqft
*   Attached garage:        About 5sqft
*   Daylight basement:      about 0.6
*   Open porch:             30sqft
*   Enclosed porch:         Over 15 sqft
*   Deck:                   About 300sqft
*   Brickstone:             None
*   Bedrooms:               2.5
*   Bathhalfcount:          Less than 0.5
*   Bath3qtr count:         1
*   Bathfullcount:          1
*   Year:                   2000
*   Longitude:              Above 0 
*   Latitude:               50


**Cluster 2**

Houses in this cluster have an average of the following:
*   Sales price:            $700,000
*   First floor size:       over 1500 sqft.
*   Half floor size:        about 20sqft.
*   2nd floor size :        less than 10 sqft. 
*   Upper floor:            none
*   Total living space:     2500sqft.
*   Basement size:          about 1500 sqft.
*   Finished basement size: 800 sqft.
*   Garage basement:        300 sqft
*   Attached garage:        less than 130sqft
*   Daylight basement:      about 0.8
*   Open porch:             40 sqft
*   Enclosed porch:         6 sqft
*   Deck:                   About 200 sqft
*   Brickstone:             Less than 5%
*   Bedrooms:               4.
*   Bathhalfcount:          About 0.4
*   Bath3qtr count:         About 1
*   Bathfullcount:          1.4
*   Year:                   2000.
*   Longitude:              Above 0 
*   Latitude:               50


**Cluster 3**

Houses in this cluster have an average of the following:
*   Sales price:            $500,000
*   First floor size:       1300 sqft.
*   Half floor size:        about 80sqft.
*   2nd floor size :        less than 10 sqft. 
*   Upper floor:            none
*   Total living space:     2500sqft.
*   Basement size:          1400 sqft.
*   Finished basement size: 30 sqft.
*   Garage basement:        20 sqft
*   Attached garage:        About 150sqft
*   Daylight basement:      about 0.05
*   Open porch:             40 sqft
*   Enclosed porch:         7.5 sqft
*   Deck:                   50 sqft
*   Brickstone:             Less than 5%
*   Bedrooms:               3
*   Bathhalfcount:          About 0.3
*   Bath3qtr count:         About 0.3
*   Bathfullcount:          1
*   Year:                   2000.
*   Longitude:              Above 0 
*   Latitude:               50


**Cluster 4**

Houses in this cluster have an average of the following:
*   Sales price:            Over $800,000
*   First floor size:       over 1500 sqft.
*   Half floor size:        about 30sqft.
*   2nd floor size :        Over 1500 sqft. 
*   Upper floor:            Less than 10%
*   Total living space:     Over 3500 sqft.
*   Basement size:          about 200 sqft.
*   Finished basement size: About 150 sqft.
*   Garage basement:        20 sqft
*   Attached garage:        About 500
*   Daylight basement:      about 0.08
*   Open porch:             Over 150 sqft
*   Enclosed porch:         5 sqft
*   Deck:                   About 100 sqft
*   Brickstone:             Less than 5%
*   Bedrooms:               More than 4.
*   Bathhalfcount:          More than 0.6
*   Bath3qtr count:         About 0.6
*   Bathfullcount:          More than 2
*   Year:                   2000.
*   Longitude:              Above 0 
*   Latitude:               50
A Bar Chart representation of the clusters.

The graph above indicates that houses in cluster 4 are the most expensive, with an average sales price of about 900,000 dollars. Houses in cluster 0 are the next most expensive set, with average sales price of about 800,000 dollars. Houses in cluster 1 and 2 have the same average sales price of about 700,000 dollars. The least expensive set of houses are in cluster 3 with an average sales price of about 500,000 dollars.

![barcharts](https://user-images.githubusercontent.com/95732821/176504315-0aa84299-540e-442a-89a4-20bf2c0b8a7f.png)

# Phase 2: Neural Network Regression






