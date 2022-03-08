# Spatial-Cluster-Analysis-Crime-in-Cracow
The aim of the project was to determine areas with increased intensity of recorded
of recorded offences in Krakow.
In the analysis we tested algorithms such as:
- K-Means
- HDBSCAN
- OPTICS
- BIRCH
- Spectral-clustering
- DBSCAN
- MeanShift
- Agglomerative Clustering (linkage=Ward)
- Gaussian Mixture

In my personal opinion the BIRCH and HDBSCAN algorithms worked best in this situation BIRCH because of the very good results in the quick selection of hyperparameters and HDBSCAN because handled the noise very well.
Each algorithm agrees with the hypothesis that a fairly large gathering of crime is located in
the area of Krakow's Main Market Square.
Other fairly large concentrations are in Mistrzejowice, Bieńczyce, Prądnik Czerwony and parts of Czyżyny.
Keep in mind that our algorithms worked on incomplete data, so they will not show us
of every cluster of crimes, but it gives us some insight into the matter.
Due to these unsupervised methods we can make many business and personal
decisions, e.g.
- it will help us to determine whether the price of the house/apartment is adequate
- we will know whether it is worth investing in more resources to protect the house and our health
- whether it is worth opening a store with luxury goods in a given neighborhood
And we can draw conclusions on many other levels e.g:
- we can speculate on the wealth of a given area by the amount of crime, usually these are poor
neighborhoods

There are many conclusions we can draw, mainly it depends on the problem we have.


![Screenshot from 2022-03-08 19-21-59](https://user-images.githubusercontent.com/81774440/157301622-d66ad23c-1f8f-4f06-b3b3-90b8b97bcd64.png)

