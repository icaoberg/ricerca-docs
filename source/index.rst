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
ricerca is a python implementation of the Feedback Adaptive Loop for Content-Based Retrieval (FALCON) algorithm as described in the article

* Leejay Wu, Christos Faloutsos, Katia P. Sycara, and Terry R. Payne. 2000. `FALCON: Feedback Adaptive Loop for Content-Based Retrieval <http://www.cs.cmu.edu/~christos/PUBLICATIONS/vldb2k-falcon.pdf>`_. In Proceedings of the 26th International Conference on Very Large Data Bases (VLDB '00), Amr El Abbadi, Michael L. Brodie, Sharma Chakravarthy, Umeshwar Dayal, Nabil Kamel, Gunter Schlageter, and Kyu-Young Whang (Eds.). Morgan Kaufmann Publishers Inc., San Francisco, CA, USA, 297-306.

Dependencies
============
ricerca uses the following python packages

- numpy
- scipy
- tables

To install this prerequisited in Ubuntu 12.04::

	sudo apt-get install update
	sudo apt-get install python-numpy python-scipy python-tables

Installation
============
The source for ricerca can be found in 

- `github <https://github.com/icaoberg/ricerca>`_

For convenience, two alternative copies are also kept up to date

- `bitbucket <git@bitbucket.org:icaoberg/ricerca.git>`_
- `codeplex <https://ricerca.codeplex.com/>`_

To install the latest copy of ricerca, run::

	git clone git@github.com:icaoberg/ricerca.git
	cd ricerca
	sudo python setup.py install
	cd ..

If you wish to install a copy of ricerca in your home directory, run::

	git clone git@github.com:icaoberg/ricerca.git
	cd ricerca
	sudo python setup.py install --home=~/
	cd ..
