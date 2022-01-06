# Jedha Uber Project final (Unsupervised machine learning)
Objective is to create algorithms that will determine where are the hot-zones that drivers should be in :

* Create an algorithm to find hot zones
* Visualize results on a nice dashboard.

A special effort was made to stratify the data by day and hour, considering the high volume of data.

Concerning Kmeans, different methods have been used to determine, as well as possible, the number of clusters  : silhouette /elbow and a test of clusteval package.

Concerning DBSCAN, the search for hyper parameters (esp, min_sample and leaf_size) allowed me to learn a lot, even if the results are not necessarily good.

I finally changed my mind about the plotly library which allows to create nice interactive maps.

If the figures are not displayed, you can have look at this folder where they are all saved : https://drive.google.com/drive/folders/11EFFyk1yzj-npjQv-9RbdUkLZ5WMR5Xv?usp=sharing
I also enclosed google drive links for each figure in the notebook.

For example : 

![image](https://user-images.githubusercontent.com/32369680/148319738-86f620d9-c98c-41cf-afb1-6ca739b237be.png)
* Centroids are marked my cars; Red marks are for specific venues (rooftops, bars, ...)

The notebook can also be seen at this address : https://colab.research.google.com/drive/1CASOyIvANlEoTSDhPlQ90n3EJ3nhe1pR?usp=sharing
##What more could be done?

By running the code several times it turned out that the parameters could vary from simple to double (...)
Considering the very large size of the dataset, it would probably be relevant to make about fifteen runs to average the parameters. We could then perhaps have a robust diagnosis
