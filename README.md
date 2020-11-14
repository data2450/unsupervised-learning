# unsupervised-learning
unsupervised learning involves tasks that operate on datasets without labeled responses or target values 

>instead the goal is to capture interesting structure or information 

**Applications of unsupervised learning**

>visualize structure of complex dataset

>density estimation to product probablities of events 

>compress and summarize the data

>extract features for supervised learning

>discover important clusters or outliers

# two types of unsupervised learning
1)**Transformations** : process that extract or compute information

2)**clusterings**  : -find groups in the data ,-assign every point in the dataset to one of the groups

# Transformations
a)**density estimation**:calculate a continous probablity density over the feature space , given a set of discrete samples in that feature space .with the density estimate ,we can estimate how likely any given combination of feature is to occure. gives a general estimate for how likely it would be to observe a particular measurement in some area of that space. eg:kernal density from sklearn

b)**Dimensionality reduction**: >find an approximate version of ure dataset using fewer features
                                used for exploring & visuvalizing a dataset to understand grouping or relationship
                          >ofen visuvalized using a 2-dimensional scatterplot 
                           >also used for comparisson ,finding feature for supervised learning
                          >one dimensional approximation is obtained by projecting the original points onto the diagonal line and using their position on that line as new  single  feature

                                 
   
   
   i)**PCA(principle component analysis)**: important form of dimensionality reduction , It takes cloud of original datapoints a rotation of fit .so the dimension are statistically uncorrelated .PCA then drops all the most informative initial dimensions that capture most of the variation in the original dataset.    
   
   It can be thought of as a projection method where data with m-columns (features) is projected into a subspace with m or fewer columns, whilst retaining the essence of the original data.


# clustering
find a way to divide a dataset into groups[clusteres]

datapoints within the same cluster sholud be 'closer' or similar in some way

datapoints in different clusters sholud be far apart or different 

clustering algorithms output a cluster memership index for each datapoint

**Hard cluster**:each datapoint belongs to exactly one cluster

**soft cluster**:each datapoint is assigned a weight score or probablity of membership for each cluter

# k-means clustering
1.Initialisation :pick the n.o of clusters 'k' u want to find ,then pick k random points to serve as an initial guess for the cluter centers 

2)STEP A: assign each datapoint to the nearest cluster center

3)STEP B:update each cluter center by replacing it with the mean of all points and assingned tp that cluster in (STEP A )

REPEAT STEPS A AND B

the centers converge to a stable solution,  These centers are considered as the final clusters

**limitations of k-meansclustering**: *works well for simple cluters that are same size well-separated ,globular shapes

*does not do well for irregular ,complex dataset



A glomm
