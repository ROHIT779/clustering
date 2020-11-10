# Cluster formation of the states/countries based on number of hospital beds available
## Dataset link and info
The dataset has been downloaded from https://www.kaggle.com/ikiulian/global-hospital-beds-capacity-for-covid19.
The zip file contains datasets for different countries and continents.
Each dataset contains number of beds for states(if the dataset is about a country) or for countries(if the dataset is about continents/world)
# Objective
1. Creating graphs for each dataset
2. Creating clusters using K-means manually by coding
3. Creating clusters using K-means from Scikit-learn package
4. Comparing two sets of clusters by computing matching percentage of the two sets(eg. if state A and state B are in same clusters when creating clusters using scikit-learn, but they are in different clusters when creating clusters manually, then the two sets of clusters disagree for this pair of states, so there is no match, otherwise a match)
