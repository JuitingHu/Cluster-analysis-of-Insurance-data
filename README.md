# Cluster analysis of Insurance data

The project is done by two other classmates and I in cooperation with the car insurance company.

Nowadays, most insurance companies use machine learning widely to help their business operations. It is common to see supervised learning applied to customer segmentation, claims and risks prediction and fraud detection. These supervised learning tasks usually include various numeric and categorical features. (numeric = customer age, vehicle age... ; category = whether or not the car is manual or automatic...) However, some high cardinality categorical variables (hccv) are hard to deal with because there are many levels such as vehicle type. To deal with this, further information is gathered on the hccv to form a new dataset and a lower dimension representation of the dataset is found which can be input into the models.

This dataset provided in this project is exactly this scenario. It contains 65,340 data entries and 347 features describing a hccv. The task set is to find a lower dimension representation of the data to be used in downstream tasks.

Before starting, we review lots of literature to find which analysis methods suit for this dataset. Clustering is the chosen method to do this.</br>
The reasons:</br>
▪️ Cluster is one of unsupervised learning methods.</br>
▪️ Cluster can be used in big data.</br>
▪️ Through cluster analysis, data objects are grouped into several clusters. Data objects within the same cluster are more similar, and  vice versa. This can represent a lower dimension of data.</br>

The following steps are:</br> 
▪️ Data Cleaning</br>
▪️ Distance matrix computation</br>
▪️ Using three algorithms, hierarchical agglomerative clustering(HAC), hierarchical density-based-spatial clustering of applications with noise (HDBSCAN) and k-medoids to build the models.</br> 


Further detailed information on this project is available in "BUSM130 Group Report.pdf","BUSM131_170376051_Individual_report.pdf" and "Presentation.pdf".
