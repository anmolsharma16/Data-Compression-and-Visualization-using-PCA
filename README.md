# Data-Compression-and-Visualization-using-PCA


This project would focus on mapping high dimensional data to a lower dimensional space, a necessary step for projects that utilize data compression or data visualizations. As the ethical discussions surrounding AI continue to grow, scientists and businesses alike are using visualizations of high dimensional data to explain results.

During this project, we perform K Means clustering on the well known Iris data set, which contains 3 classes of 50 instances each, where each class refers to a type of iris plant. To visualize the clusters, we will use principle component analysis (PCA) to reduce the number of features in the dataset.

Due to it's common usage for pattern recognition tasks, the iris dataset is available directly through scikit-learn. Furthermore, we will construct a Pandas DataFrame that provides descriptive statistics for the data set, as well as visualizations such as a scatter matrix.

Principal component analysis (PCA) is a statistical procedure that uses an orthogonal transformation to convert a set of observations of possibly correlated variables into a set of values of linearly uncorrelated variables called principal components.

Unless you have a heavy linear algebra background, it's easy to get lost in the eigenvectors and eigenvalues that PCA relies on. Fortunately for us, scikit-learn makes implementing PCA easy and straight forward. Here,we performed a PCA reduction to reduce the number of features in the dataset to two. As a result of this reduction, we will be able to visualize each instance as an X,Y data point.

![44536222-9758cb80-a719-11e8-9033-8219618a893b](https://user-images.githubusercontent.com/60782798/118249540-29552380-b4c3-11eb-940a-0ac004ed8a9d.png)
