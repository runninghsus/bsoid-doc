Installation and usage
======================

.. _installation:
.. _usage:

Installation
------------
The first step is to download the Anaconda_ distribution to setup a B-SOiD environment.

.. _Anaconda: https://www.anaconda.com/


To use B-SOiD, first download it:

.. code-block:: console

   (base) C:/Users/username> git clone https://github.com/YttriLab/B-SOID.git

Create an environment:

.. code-block:: console

   (base) C:/Users/username> cd B-SOID
   (base) c:/Users/username/B-SOID> conda env create -n bsoid_v2 -f requirements_win.yaml (windows)

Activate that environment:

.. code-block:: console

   (base) C:/Users/username> conda activate bsoid_v2

Usage
-----

Run the streamlit application:

.. code-block:: console

   (base) C:/Users/username> streamlit run bsoid_app.py