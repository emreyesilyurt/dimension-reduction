##### Turkish text: [Medium - Emre YESILYURT](https://medium.com/@emreyesilyurt/makine-%C3%B6%C4%9Frenmesi-boyut-i%CC%87ndirgeme-dimension-reduction-pca-f7e6d366cc14)

## Dimension Reduction 

The number of entries or features in a data set is the size of that data set.

With size reduction techniques, we reduce the number of input variables in a data set. Excess size also requires a lot of resources, makes visualization difficult, can decrease performance. That's why size reduction is frequently used in machine learning models in many respects.

![](https://miro.medium.com/max/220/1*-zvCu5BF0W3sAwF39NgPdQ.gif)

In other words, the main purpose of dimension reduction is to increase the usability of data while reducing the cost to us.


After performing this process, we are actually looking at the data from a different point. Looking at the data from a different point means that it can be inferred with new qualities.

![alt-text](https://miro.medium.com/max/577/1*TlVYvzPFFpZupHL1VTNChg.png)

We may experience data loss while at the same time extracting new attributes. For example, suppose you are moving from 3D space to 2D space.

![alt-text](https://miro.medium.com/max/700/1*ZK4Soly4i2x0Z1ijpxuijA.png)

When you examine visually, you will see that data points on the same plane in 3 dimensions disappear when 2 dimensions are reduced.


In other words, the PCA algorithm has no guarantee that it will not lose data.
The basic working principle of PCA is to find the most relevant data points and combine them linearly. That is, the variables that are related to each other are matched and a sequence that can be summarized is created.


![alt-text](https://miro.medium.com/max/1000/1*vXQ5sgMF0XmiY4Jc6gJVwA.png)
