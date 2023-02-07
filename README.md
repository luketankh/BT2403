# BT2403
BT2403 Facility Location Planning in Python and Excel

This is a project done for NTU Business Analytics Module : BT2403 Service Operations Management. 
It involves selecting an ideal facility location for starting a business that delivers xy product.

Our goal is to situate p number of facilities across n locations such that we can 
1. Improve the service experience of the consumer by minimising the worst-case distance, k (the furthest any group of customers have to walk to the nearest facility location)
2. Reduce the effect of cannibalization between service facilities by ensuring an arbitrary minimum distance between them 
3. Ensure that we set up an ideal number of facilities (ideal p) using marginal cost-benefit analysis. (i.e tradeoff between p = 3 and p = 4)

Using SPOPT and Folium, together with the SGOneMap API, you can find the geospatial analysis in scrape.ipynb. 

### USE THIS LINK TO VIEW THE NOTEBOOK WITH FOLIUM MAPS ### 
https://nbviewer.org/github/luketankh/BT2403/blob/main/scrape.ipynb

Since Gurobi/Pyomo/Scipy are not yet capable of handing min-max problems, the final model was done in excel. 
DISCLAIMER : You will not be able to run the excel file using default excel solver.
