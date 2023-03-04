# SelfOrganizinMaps

The following is toy problem, displaying the code for Self Organizing Maps. 

Self Organizing Maps are learning methods from Competitive Learning paradigm. We initialize a tensor or matrix with random values, and store a randomized vector on each coordinate of the matrix. Now for each training example encountered, we can check whcich vector on which map, holds the closest representation of the training sample.

Now we iterate this over all training samples, and we can get a visual representation of our training sample. It can described as an unsupervised algorithm. it could be possible also, for feature extraction using this methodology, or class assignment for unsupervised case. 

![500px-Somtraining svg](https://user-images.githubusercontent.com/17704242/222906029-aeebf8a6-8894-4884-b958-139ee28f6e89.png)

Few are results of taking a matrix training sample, with RGB colors, 

And aligning the SOM to match our intial training data.![som image](https://user-images.githubusercontent.com/17704242/222905952-bcd3f159-8dd2-4dd4-8a3d-bf10ee2876c8.png)


And below is an example, of when we change our $\sigma$ for our distance function. 

Credit goes to :
- https://en.wikipedia.org/wiki/Self-organizing_map
- https://stackabuse.com/self-organizing-maps-theory-and-implementation-in-python-with-numpy/
