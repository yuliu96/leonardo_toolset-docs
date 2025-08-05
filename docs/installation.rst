Installation
============

Leonardo requires Python>=3.10. We highly recommend using :mod:`conda` 
virtual environment to install and operate Leonardo.

PyPI
-----

CPU version
~~~~~~~~~~~

To use Leonardo with CPU, install Leonardo using:

.. code-block:: bash

    conda create -n leonardo python=3.10
    conda activate leonardo
    pip install leonardo_toolset

Additional Napari plugins can be installed separately:

.. code-block:: bash

    pip install lsfm_destripe_napari
    pip install lsfm_fusion_napari

Leonardo has now been tested on Linux and Windows. 
Leonardo may have issues on macOS caused by third-party dependencies, specifically resulting in a "metadata-generation-failed" error.

GPU version
~~~~~~~~~~~

To use Leonardo with GPU:

- Setup Pytorch according to your own system setting, following the `official guideline <https://pytorch.org/get-started/locally/>`_.
- Setup Jax according to your own system setting, following the `official guideline <https://jax.readthedocs.io/en/latest/installation.html>`_ (Optional).
- Install Leonardo following the instructions under Section CPU version.

Development Version
--------------------

To work with the latest development version, install from GitHub using:

.. code-block:: bash

    pip install git+https://github.com/peng-lab/leonardo_toolset.git
