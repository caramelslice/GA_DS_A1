# GA Assignment1 Data Mining Algorithms Readthru
Assignment description can be obtained [here](https://github.com/podopie/DAT18NYC/blob/master/assignments/01-data_mining_algorithms_readthru.md)

Student name: Julie (Xiaoshu) Qiu
Date: 2 Feb 2015

# Data Mining Algorithms Readthru
*Due Date: 2/2/2015*

## Objectives

* familiarize yourself with the common data mining problems and algorithms
* focus and learn about one in particular

## Assignment

Read through Oracle's top level page on [data mining algorithms](http://www.oracle.com/technetwork/database/enterprise-edition/odm-techniques-algorithms-097163.html). Keep track of words you don't understand, recognize, heard before, etc.

Under "algorithms," pick one link and read through the text. in a markdown file, write up the following:

* What was the name of the algorithm you read about?
Principal Components Analysis (PCA) and Singular Vector Decomposition (SVD)
These two are essentially closely replated. 

* What data problem does it solve? (listed under Technique on previous page)

Principal Components Analysis (PCA): creates new fewer composite attributes that respresent all the attributes.
Singular Vector Decomposition: established feature extraction method that has a wide range of applications.

* In layman's terms, what does the algorithm do? Even if you aren't sure, that's okay! Just try your best--we're not looking for perfect answers.
PCA is commonly used in Dimensionality Reduction. We have a lot of variables that are correlated but we can reduce the number of variables by categorizing them, find the best matrix with fewer variables that still can explain the data.
SVD deals with data compression. 

* Come up with up to three applications of this algorithm in business. Try relating it to your own job or line of work, your other data interests, or what have you.
SVD and PCA are commonly use dto solve complex systems such as neuroscience, photoscience,
meteorology and oceanography - the number of variables to measure can be unwieldy and at times even deceptive, but the underlying dynamics can often be quite simple.


Application 1:
We are trying to understand some phenomenon by measuring
various quantities (e.g. spectra, voltages, velocities,
etc.) in our system. But we cannot figure out what is happening because the data
appears clouded, unclear and even redundant. 


Application 2: Image processing (source: UCLA)
We can use SVD to compress and recreate images. For example, we read in a jpeg (pansy.jpg) and plots it, first in color (when the image is stored as three matrices--one red, one green, one blue) and then in grayscale (when the image is stored as one matrix). Then, using SVD, we can essentially compress the image. We can also recover the image to varying degrees of detail as we recreate the image from different numbers of dimensions from our SVD matrices. We can see how many dimensions are needed before you have an image that cannot be differentiated from the original.


Application 3: neuroscience (source: wikipedia)
In neuroscience, PCA is also used to discern the identity of a neuron from the shape of its action potential. Spike sorting is an important procedure because extracellular recording techniques often pick up signals from more than one neuron. In spike sorting, one first uses PCA to reduce the dimensionality of the space of action potential waveforms, and then performs clustering analysis to associate specific action potentials with individual neurons.

