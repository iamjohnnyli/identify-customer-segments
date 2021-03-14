# Self Learn Project: Identify Customer Segments

This is one of the Udacity Data Scientist Nanodegree Project. This project aims to identify segments of the population from the core customer base for a mail-order sales company in Germany. Therefore, these segments can then be used to direct marketing campaigns towards audiences with the highest expected rate of returns.

The techniques I used in this project include:  

1. Data cleaning  
1. Encoding and processing mixed-type feature  
1. Feature Scaling and Dimensionality Reduction
1. Clustering
1. Performance improvement with OpenBLA

<!-- ## Installation 

Please install Jupyter Notebook to review and execute the code in the notebook. Please run ```pip install -r requirements.txt``` in your shell for required python packages. -->

## Data

The data files associated with this project (not included in this repository):

- `Udacity_AZDIAS_Subset.csv`: Demographics data for the general population of Germany; 891,211 persons (rows) x 85 features (columns).
- `Udacity_CUSTOMERS_Subset.csv`: Demographics data for customers of a mail-order company; 191,652 persons (rows) x 85 features (columns).
- `Data_Dictionary.md`: Detailed information file about the features in the provided datasets.
- `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns

## Analysis Structure

1. Data exploration and data cleaning (85% of the analysis)
2. Feature Engineering (One Hot, Scaling, and PCA)
3. Clustering with k-means


## Conclusion

Cluster 2 is overrepresented, and cluster 3 is underrepresented. Compare two groups of diagrams, we can find that there are many differences in demographics between overrepresented and underrepresented people. 

- Membership in Green Avantgarde: In cluster 2, more people are the member of Green Avantgarde
- Personality - Dutiful: People in cluster 3 have a higher affinity 
- Number of adults in household: In cluster 2, most households have 1 to 4 adults.
- Distance from building to the point of sale: People in cluster 3 are closer to Pos than people in cluster 2.
- Wealth / Life Stage Typology: More people in cluster 2 are upper class
- Type of Building: Most builds in cluster 2 are residential buildings.
- Social status: Most people in cluster 2 are top earners, and most people in cluster 3 are house owners.
- Age: Most people in cluster 3 from the 40s' and most people in cluster 3 from the 50s'.



## Licensing and Acknowledgements

Udacity Data Scientist provided the starting code for this project.
Udacity partners at Bertelsmann Arvato Analytics provided the data.
