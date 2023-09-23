### Reading: k-Means Initialization

K-means requires initialization of the k cluster centers. One method is random initialization, which can work poorly.  
Here are some initialization techniques that can work better:

- [k-means++](https://en.wikipedia.org/wiki/K-means%2B%2B)

### Optional Reading 

The MLlib implementation of K-Means includes a parallelized variant of the k-means++ method called kmeans||.

- [kmeans ||](http://theory.stanford.edu/~sergei/papers/vldb12-kmpar.pdf)