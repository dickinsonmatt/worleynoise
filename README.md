# Worley noise
Another algorithm for making 'structured noise' that I attempted.

I found it much easier than Perlin noise because it's all based on Euclidean distances. In some versions of the algorithm, you generate the number of feature points based on a Poisson distribution for each cell, but I decided to go with a slightly simpler version where you only generate one feature point per cell. 

