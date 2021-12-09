=============================
Demo-Notebooks-CMIP6
=============================

This repository lets you try out creating basic plots from CMIP6 Earth System Model data.

Try out a notebook by clicking on this icon: |Binder|

Usage notes:

**2021 July 26**

- If a dialog box pops up after Binder loads, click *Cancel*

See http://pangeo.io for more information.

**2021 Dec 08**

- Unfortunately Pangeo Binder is currently down (https://github.com/pangeo-data/pangeo-binder/issues/195) so the Binder badge doesn't work, but the notebooks should run on a standard Jupyter installtion. You may need to adjust dask settings, try replacing any dask_gateway code with the following:

``from dask.distributed import Client``

``client = Client(n_workers=4)``




.. _pangeo.binder.io: http://binder.pangeo.io/

.. |Binder| image:: http://binder.pangeo.io/badge.svg
    :target: http://binder.pangeo.io/v2/gh/jdldeauna/demo_notebooks_cmip6/master



