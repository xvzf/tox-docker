==========
TOX DOCKER
==========

Docker with Python `2.7`, `3.4`, `3.5` and `3.6` together with tox
preinstalled for comfortable testing


Running tests with the image
============================

In the project root, run:

.. code-block:: bash

    docker run --rm -v $(pwd):/src xvzf/tox
