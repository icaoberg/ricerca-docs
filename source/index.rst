.. ricerca documentation master file, created by
   sphinx-quickstart on Fri Jul 19 10:46:19 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

ricerca
=======

Contents:


.. toctree::
   :maxdepth: 2

   ricerca
   history

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

About
=====
ricerca is one of the python packages that was developed for `OMERO.searcher <http://murphylab.web.cmu.edu/software/searcher/>`_, an open-source content-based image search tool for the cell and computational biology community as described in

* Baek Hwan Cho, Ivan Cao-Berg, Jennifer Ann Bakal and Robert F. Murphy. 2012. `OMERO.searcher: content-based image search for microscope images <http://www.nature.com/nmeth/journal/v9/n7/full/nmeth.2086.html>`_. Nature Methods 9, 633-634.

ricerca is an implementation of the Feedback Adaptive Loop for Content-Based Retrieval (FALCON) algorithm as described in

* Leejay Wu, Christos Faloutsos, Katia P. Sycara, and Terry R. Payne. 2000. `FALCON: Feedback Adaptive Loop for Content-Based Retrieval <http://www.cs.cmu.edu/~christos/PUBLICATIONS/vldb2k-falcon.pdf>`_. In Proceedings of the 26th International Conference on Very Large Data Bases (VLDB '00), Amr El Abbadi, Michael L. Brodie, Sharma Chakravarthy, Umeshwar Dayal, Nabil Kamel, Gunter Schlageter, and Kyu-Young Whang (Eds.). Morgan Kaufmann Publishers Inc., San Francisco, CA, USA, 297-306.

License
-------
| Copyright (C) 2011-2014 Murphy Lab
| Ray and Stephanie Lane Center for Computational Biology
| School of Computer Science
| Carnegie Mellon University

You should have received a copy of the license along with this program. For additional information visit http://murphylab.web.cmu.edu/software.

Authors
-------
| Ivan Cao-Berg, Jennifer Bakal, Baek Hwan Cho and Robert F. Murphy
| `Ray and Stephanie Lane Center for Computational Biology <http://lane.compbio.cmu.edu/>`_
| `School of Computer Science <http://www.cs.cmu.edu/>`_
| `Carnegie Mellon University <http://www.cmu.edu/>`_

Dependencies
============
ricerca uses the following python packages

- `numpy <http://www.numpy.org/>`_
- `scipy <http://www.scipy.org/>`_
- `tables <https://pypi.python.org/pypi/tables>`_

To install this prerequisites in Ubuntu 12.04, run in terminal::

	sudo apt-get install update
	sudo apt-get install python-numpy python-scipy python-tables

If you wish to install the dependencies using pip::

	sudo pip install numpy scipy
	sudo pip install numexpr cython tables

Installation
============
The source for ricerca can be found in 

- `github <https://github.com/icaoberg/ricerca>`_

For convenience, an alternative copy is also kept up to date

- `bitbucket <git@bitbucket.org:icaoberg/ricerca.git>`_

To install the latest version of ricerca from the repository, run::

	git clone git@github.com:icaoberg/ricerca.git
	cd ricerca
	sudo python setup.py install
	cd ..

If you wish to install a copy of ricerca in your home directory, run::

	git clone git@github.com:icaoberg/ricerca.git
	cd ricerca
	sudo python setup.py install --home=~/
	cd ..

If you wish to install a copy of ricerca using virtualenv, run::

	virtualenv venv
	cd venv
	. ./bin/activate
	pip install numpy 
	pip install scipy 
	pip install numexpr 
	pip install cython 
	pip install tables
	mkdir src
	cd src
	git clone git@github.com:icaoberg/ricerca.git
	cd ricerca
	python setup.py install
	cd ../../
