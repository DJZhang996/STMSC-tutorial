
Installation
============

The STMSC package is developed based on the pytorch framework and can be implemented on both GPU and CPU. 
We recommend running the package on GPU. Please ensure that pytorch and CUDNN are installed correctly. To run STMSC, all dependencies included in the file 'requirement.txt' need to be installed. 

Step 1: Clone the Repository
--------------------------------

Dowloading the package from https://github.com/bliulab/STMSC

.. code-block:: python

   git clone https://github.com/bliulab/STMSC.git
   cd STMSC

Step 2: Create a Conda Environment
--------------------------------------
We recommend creating a separate environment for running STMSC:

.. code-block:: python

   # Create a conda environment named env_STMSC with Python 3.8
   conda create -n env_STMSC python=3.10
   # Activate the environment
   conda activate env_STMSC
   
Step 3: Install Required Packages
----------------------------------
For Linux:

.. code-block:: python

   pip install -r requirements.txt

Step 4: Install STMSC
----------------------------------

.. code-block:: python

   python setup.py build
   python setup.py install