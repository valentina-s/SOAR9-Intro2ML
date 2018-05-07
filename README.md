# Introduction to Machine Learning

This repo contains materials for the Introduction to Machine Learning Tutorial during the SOAR 9 Meeting at the University of Washington, Seattle, May 2018.

In this tutorial we will introduce both supervised and unsupervised methods for learning from data, explain how to evaluate the performance of the introduced algorithms, and discuss approaches for handling temporal and spatial correlations in the signals.

We will use a dataset of mosquito wingbeat recordings from 6 species. The data comes from this kaggle dataset [Wingbeats](https://www.kaggle.com/potamitis/wingbeats/data).

The data collection process is described in the following paper:

[http://ieeexplore.ieee.org/abstract/document/7482663/](http://ieeexplore.ieee.org/abstract/document/7482663/).

We will use Anaconda Python 3.6.

To run things locally, please install it on your laptop in advance:

https://www.anaconda.com/download

You can start a notebook server by running

```
  jupyter notebook
```

You can obtain the notebooks by downloading the whole repo from github (find the github button).

To use azure notebooks log-in https://notebooks.azure.com/ (it should work with your uw email).

Navigate to https://notebooks.azure.com/anon-ag8bvg/libraries/SOAR9-Intro2ML

and click clone (this will create a local copy of the notebooks and you can edit them).

If you have some problems installing `keras` from within the last notebook, try

```
  conda uninstall --yes numba
  conda uninstall --yes keras
  conda install --yes keras
```

