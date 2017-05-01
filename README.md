# STA-663-FINAL-PROJECT
STA 663 Final Project Spring 2017

Tema Members: Jiancong Zhu & William Eastman

In this project, we implement the kmeans|| initialization algorithm and kmeans++ initialization algorithm and compare 
them with the random selecting initialization algorithm.

We apply the three initialization algorithms for three GuassMixture datasets and the spambase dataset. 

We speed up the algorithms using broadcasting and jit respectively. 

Generally, the kmeans|| and kmeans++ are better than random selecting algorithm in cost and iterations especially when the 
points in the dataset spread widely.

Kmeans|| and kmeans++ both have their advantages and disadvantages. When the dataset is massive, kmeans++ may be not proper 
because the running time is too long.
