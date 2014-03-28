PyToolz Tutorial for PyData 2013 - NYC
======================================

The tutorial `video`_ is now available.


Requirements
------------

    Python 2.6, 2.7, 3.2, 3.3

    pip install toolz


Notebooks
---------

You can open the tutorial notebooks in the IPython's notebook viewer:

-  `map-filter-reduce-groupby`_
-  `composition`_
-  `curry`_
-  `wordcount`_
-  `laziness`_
-  `genomics`_
-  `fib-memoize`_
-  `groupby-github`_


.. _PyToolz Tutorial for PyData 2013 - NYC: https://github.com/mrocklin/pydata-toolz
.. _map-filter-reduce-groupby: http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/1-map-filter-reduce-groupby.ipynb
.. _composition: http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/2-composition.ipynb
.. _curry: http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/3-curry.ipynb
.. _wordcount: http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/4-wordcount.ipynb
.. _laziness: http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/5-laziness.ipynb
.. _genomics: http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/6-genomics.ipynb
.. _fib-memoize: http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/7-fib-memoize.ipynb
.. _groupby-github: http://nbviewer.ipython.org/urls/raw.githubusercontent.com/mrocklin/pydata-toolz/master/8-groupby-github.ipynb
.. _repo: https://github.com/mrocklin/pydata-toolz
.. _slides: https://github.com/mrocklin/pydata-toolz/tree/master/slides
.. _video: https://github.com/mrocklin/pydata-toolz/tree/master/slides
.. _pytoolz intro: http://matthewrocklin.com/blog/work/2013/10/17/Introducing-PyToolz/


Data
----

Data for most of the notebooks resides in the `data` directory

Those interested in the human genome can find it at
http://hgdownload.cse.ucsc.edu/goldenPath/hg19/chromosomes/

Those interested in the Github data can find it at
http://www.githubarchive.org/


Errata
------

After the talk Jake Vanderplas showed me that indeed `numpy` does support
accumulation on any binary operator.  Try the following in `ipython` for a
list of supported binops

    import numpy
    numpy.*.accumulate?
