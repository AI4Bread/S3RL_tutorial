.. S3RL documentation master file, created by
   sphinx-quickstart on Wed Apr 16 19:43:51 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Installation (pyG framework)
============

Software Dependencies
---------------------
.. code-block:: python

   scanpy
   pytorch
   torch-geometric
   anndata
   numpy
   pandas
   matplotlib

To use the Mclust-based clustering component in S3RL, please install the `rpy2` Python package and the `mclust` R package:

- rpy2: https://pypi.org/project/rpy2/  
- mclust: https://cran.r-project.org/web/packages/mclust/index.html

Installation
------------

Download the S3RL code from GitHub: https://github.com/AI4Bread/S3RL

.. code-block:: bash

   git clone https://github.com/AI4Bread/S3RL.git
   cd S3RL
   python setup.py build
   python setup.py install

To use S3RL in Python:

.. code-block:: python

   import S3RL