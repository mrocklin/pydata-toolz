PyToolz Tutorial for PyData 2013 - NYC
======================================


Requirements
------------

    Python 2.6, 2.7, 3.2, 3.3

    pip install toolz


Video
-----

The tutorial [video](http://vimeo.com/80096814) is now available on Vimeo.


Notebooks
---------

The following links will open the tutorial notebooks in IPython's online notebook viewer:

* [map-filter-reduce-groupby](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/1-map-filter-reduce-groupby.ipynb)
* [composition](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/2-composition.ipynb)
* [curry](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/3-curry.ipynb)
* [wordcount](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/4-wordcount.ipynb)
* [laziness](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/5-laziness.ipynb)
* [genomics](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/6-genomics.ipynb)
* [fib-memoize](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/7-fib-memoize.ipynb)
* [groupby-github](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/8-groupby-github.ipynb)


Data
----

Data for most of the notebooks resides in the `data` directory

The human genome data can be found [here](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/chromosomes/)

The Github data can be found [here](http://www.githubarchive.org/)


Errata
------

After the talk Jake Vanderplas showed me that indeed `numpy` does support
accumulation on any binary operator.  Try the following in `ipython` for a
list of supported binops

    import numpy
    numpy.*.accumulate?

