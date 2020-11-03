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

                                > used for exploring & visuvalizing a dataset to understand grouping or relationship
                                >ofen visuvalized using a 2-dimensional scatterplot 
                                >also used for comparisson ,finding feature for supervised learning
                                >one dimensional approximation is obtained by projecting the original points onto the diagonal line and using 
