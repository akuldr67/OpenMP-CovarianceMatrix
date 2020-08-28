# OpenMP-CovarianceMatrix
To calculate covariance matrix of the given dataset by OpenMP  
iris.data is given as a dataset. Read the data from file and ignore the last column of each row in dataset.  

To compile:
```
gcc -fopenmp -o cov cov.c
```
where cov is the name of the object file.

To run:
```
./cov
```
Number of threads will be asked at the starting when the code is run. You can give any positive integer value in that. But generally 3-4 threads give best results.
