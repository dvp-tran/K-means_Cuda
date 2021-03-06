# Kmeans with Theano

## Objective

In this project, the authors performed K-means to images, through <a href= http://deeplearning.net/software/theano/> Theano </a>, in order to get <a href =https://en.wikipedia.org/wiki/Color_quantization >  color quantization</a>. 

## Execution

In order to use your GPU, use the following code : 
```
THEANO_FLAGS=floatX=float32,device=gpu,allow_gc=False,nvcc.flags=-D_FORCE_INLINES,nvcc.fastmath=True jupyter notebook
```

## Organisation
- data/images : contains many images, with different size, used in the Jupyter notebook
- notebook : contains two Jupyter notebook
  - Theano_kmeans_colour_quantification_v4-Benchmark : a Jupyter notebook used for some benchmark
  - Theano_kmeans_colour_quantification_v5: a Jupyter notebook for a different dataset
  - Theano_kmeans_colour_quantification-Huge_File: a Jupyter notebook for processing very large images over 1Go (> 500 Millions pixels)
- report : contains a rapport, written in French, explaining the project  
- results : contains some results obtained via Kmeans 

## Illustration :

![alt tag](https://github.com/dvp-tran/Theano_Kmeans/blob/master/results/Couverture.png)