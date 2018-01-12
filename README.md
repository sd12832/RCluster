# RCluster

![N|Solid](http://www.paperboardpackaging.org/images/default-source/School-Logos/sjsu-primary-mark_web.png?sfvrsn=0)

>“You cannot eat a cluster of grapes at once, but it is very easy if you eat them one by one.” - **Jacques Roumain**

I set out on this project in order to investigate why there weren't any projects that investigated K-Medians and its functionality within the various repositories that I had explored online. I conclude my findings within the document titled **Sharan_RClusterFinal.pdf**. In order to conduct my research, I wrote this code. 

**K-Medians** clustering is a type of unsupervised learning, which is used when you have unlabeled data (i.e., data without defined categories or groups). The goal of this algorithm is to find groups in the data, with the number of groups represented by the variable *K*. This project could be of use to two different sets of people: 

  - People curious about the techniques that can be used to build any kind of clustering algorithm within Python. 
  - People who want to **investigate** how to build a modern *K-Medians* algorithm. Before you do so, please refer to research findings given in the presentation in the repository, titled **Sharan_RClusterFinal.pdf**.   

# My Data Set

The data set contained within the file *data_1024.csv*(which in fact is tab seperated), was given to me without a legitimate source. When charted, the results are as shown below: 
![DatSet](https://i.imgur.com/yh1crLW.png)

# Performance 

The performance of my classifier is as shown below: 

![Dataset2](https://i.imgur.com/wdyM01d.png)

There are four different classifiers within this repository. In order to find out more about their performance, please refer to the document: **Sharan_RClusterFinal.pdf**. 
  
# How to Run the Program 

There are in total four different clustering algorithms present within this repository. There are either Vanilla or have many modifications implemented onto them by principles from the subject of Randomized Algorithms. In order, to find out the theory behind these modificaitons please look at the attached document and the respective references within the document. 

To run a particular clustering algorithm; in this case, the Randomized K-Medians algorithm, simply type the following into a terminal: 

```sh
python rand_kmedians.py
```

Please refer to my documentation and comments in order to gain more insight into the programs. 

# Tech Used
- *matplotlib*
- *numpy*
- *seaborn*
 
### Todos

- Need to improve the initialization of the Centroids [1] (An Arithmetic-Based Deterministic Centroid Initialization Method for the k-Means Clustering Algorithm).
- Do further testing to derive more conclusive results. This may require using more comprehensive data sets.
- Increase the number of dimensions to the feature vectors, to increase the robustness of my algorithm.

### References 

[1] Mayo, M.M., 2016. An Arithmetic-Based Deterministic Centroid Initialization Method for the k-Means Clustering Algorithm.

![Grapes](https://redwinelovers.files.wordpress.com/2013/06/gamay-grapes.jpg)

License
----

MIT
