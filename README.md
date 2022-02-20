## Machine Learning: Dimension Reduction

Hello, this article will explain the benefits of dimension reduction and its application.
Today, even a simple IoT sensor produces multidimensional data. First, we encounter the problem of visualizing multidimensional datasets. It is impossible to visualize a twenty-dimensional dataset. However, reducing this twenty-dimensional data set to three or two dimensions will allow visualization. In addition, calculating the distances between data points will cause quite a lot of cost in twenty-dimensional data. In other words, processing multidimensional data has high transaction costs.
![](https://miro.medium.com/max/220/1*-zvCu5BF0W3sAwF39NgPdQ.gif)
Dimension reduction is looking at the data from a different point of view. It can also be thought of as taking a picture of the data while looking from a different point of view. Looking at the data from a different perspective will lead to new qualities and features.

While introducing new features (Feature extraction), we can also lose some data. For example, let’s examine the following sample data, from 3-dimensional to 2-dimensional extension.

When you examine the image, you will see that some data points disappear when the 3-dimensional data set is reduced to 2 dimensions. This is because some overlapping data points cause complexity and disappear when moving to a different space. I must say that Principal Component Analysis (PCA) is not a guarantee of not losing data.
Principal Component Analysis’s working principle is in its simplest form; Finding the most relevant data points in as many clusters as the number of dimensions to reduce and combining them linearly. It uses eigenvectors and Eigen matrices to perform all these operations.
For a more professional statistical explanation, you can watch the video below. The purpose of this article is to instill an essential vision.

https://www.youtube.com/watch?v=WW3ZJHPwvyg
