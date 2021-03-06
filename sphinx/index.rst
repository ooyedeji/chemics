Chemics Documentation
=====================

Chemics is a Python package for developing reactor models.

Requirements
------------

The Anaconda or Miniconda distribution of Python is preferred for scientific applications.

- Python 3
- NumPy

Installation
------------

Stuff here.

Usage
-----

Functions in the chemics package are called with the usual dot syntax for accessing module features. The example below imports the chemics package then calculates the density of a gas based on its molecular weight, pressure, and temperature.

.. code-block:: python

    import chemics as cm
    cm.rhog(28, 170100, 773)

Modules
-------

The following modules are available in the chemics package:

.. toctree::
   :maxdepth: 2

   fluidization
   thermodynamics

Package index and modules
-------------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
