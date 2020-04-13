# Advanced-Recommender-Systems
The purpose of this notebook is to implement a location-based recommender system from regular location-based social network (LBSN) data.
Usually LBSN data give precise information regarding the locations visited by the users.
These data also reveal who are the friends of the users.
These two information (geographical + social) can be exploited into a standard collaborative filtering approach.

We build in this notebook blocks of the model developped by Zhang and Chow, 2013, iGSLR: personalized geo-social location recommendation: a kernel density estimation approach.
Source: https://dl.acm.org/doi/10.1145/2525314.2525339

We also used the Surprise framework in order to implement our recommender system.
Documentation: https://surprise.readthedocs.io/en/stable/index.html

# Data
The input dataset for this lab was collected from Gowalla, a popular LBSN that is often used to test recommendation methods with geographical dimensions.
In practice the dataset contains user profiles, user friendship, location profiles, and users’ check-in history made before June 1, 2011.
It contains 36,001,959 check-ins made by 407,533 users over 2,724,891 locations.

Data can be downloaded here: https://snap.stanford.edu/data/loc-gowalla.html

# Context
This project was carried out as a validation of the Recommendation System course given by Marie Al-Ghossein and Jean-Baptiste Griesner as part of the Master Data Sciences at École Polytechnique.

Authors: Cédric Allain, Clotilde Miura, Manon Rivoire, Adriano Del Gallo and Saousan Kaddami
