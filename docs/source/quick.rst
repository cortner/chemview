============================
Installation and Quick Start
============================

Installing chemview with conda is fairly easy. First download anaconda (or miniconda):

http://continuum.io/downloads

To install chemview using conda you can first create an environment (optional):

.. code-block:: bash

    $ conda create -p /path/to/new/environment python
    $ source activate /path/to/new/environment

then, you can install chemview directly from the binstar channel.

.. code-block:: bash

    $ conda install -c http://conda.binstar.org/gabrielelanaro

or, for the development version you can manually install the dependencies:

.. code-block:: bash

    $ conda install notebook
    $ conda install numpy
    $ conda install numba
    $ git clone https://github.com/gabrielelanaro/chemview
    $ cd chemview
    $ pip install .

It is also possible to install chemview using pip:

.. code-block:: bash

    pip install notebook # Jupyter 4.x
    pip install numpy
    pip install numba

    # Download and install chemview
    git clone https://github.com/gabrielelanaro/chemview
    cd chemview
    pip install .

Quick Start
-----------

In this section we'll see how to visualize a benzene molecule with chemview. To start, let's launch IPython notebook and start a new notebook.

.. code-bock:: bash

    ipython notebook

.. include:: notebooks/QuickStart.rst

Congratulation for finishing the first tutorial! You can now move on more advanced topics:

.. toctree::
    :maxdepth: 2

    representations
    interactivity
    lowlevel
