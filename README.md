![Stocks](https://www.investors.com/wp-content/uploads/2019/01/Stock-MarketUptrend-04-adobe.jpg)
# Stock Market Clustering Using Unsupervised Machine Learning Techniques
We obtained the Stock Market dataset from 'yahoo' and used Jupyter Notebook as the platform for the purpose of coding. Our methodology involves use of clustering techniques like **'K-means Clustering'**(with/without using PCA).
## What is K-Means?
k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. It is popular for cluster analysis in data mining. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances.
## What is PCA?
Given a collection of points in two, three, or higher dimensional space, a "best fitting" line can be defined as one that minimizes the average squared distance from a point to the line. The next best-fitting line can be similarly chosen from directions perpendicular to the first. Repeating this process yields an orthogonal basis in which different individual dimensions of the data are uncorrelated. These basis vectors are called principal components, and several related procedures principal component analysis (PCA).
PCA is mostly used as a tool in exploratory data analysis and for making predictive models. It is often used to visualize genetic distance and relatedness between populations.
## Dataset for unsupervised learning
The data taken is from **Yahoo** using **pandas_datareader**.
## Testing the clustering accuracy
As we see most of same type of companies are most probably clustered into same type.(eg:[Cocacola,Pepsi],[Exxon,Chevron]...).
Also 'k-means inertia' is checked which varies slightly with every run.
### Labels are predicted:
- 0 to x-1 for x clusters.
# Result =>
We also used PCA and then predicted the clusters which came out to have less correctness than K-means(Without PCA) as PCA reduces dimensionality and also looses some features along with this reduction. But, still most of the same companies could be seen together in the same cluster.

## Files included in repository are:
- **source.ipynb(Jupyter Notebook-https://jupyter.org/)**
- **source.pdf(Just a pdf print of jupyter notebook)**
<br />

***In source.ipynb, data is visualized using Non-Normalised/Normalised Graphs and MeshGrid Plots.***
