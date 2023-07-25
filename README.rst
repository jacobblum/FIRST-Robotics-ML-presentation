A Gentle Introduction Deep Learning and Computer Vision
....

To follow along with the coding tutorials, let's first install everything we'll need! 

Installation and Usage 
----------------------

Manual installation
~~~~~~~~~~~~~~~~~~~

The recommended installation is as follows. First, let's install `anaconda <https://docs.anaconda.com/free/anaconda/install/windows/>`_. `anaconda`  is an environment and package manager that will help us manage all the libraries we require! 
Once `anaconda` is installed, we can install all the packages we need.

In particular, we will need to install: `PyTorch <https://pytorch.org>`_, `torchvision <https://pypi.org/project/torchvision/>`_, `Sklearn <https://scikit-learn.org/stable/index.html>`_, `matplotlib <https://matplotlib.org>`_, and `seaborn <https://seaborn.pydata.org>`_

To install `PyTorch <https://pytorch.org>`_, select the appropriate operating system/ version options and type the following command in your terminal (this command is for
my device (macOS using `conda`), the specific command may be different for you if you're using a windows machine):

.. code-block:: bash
  
  >conda install pytorch::pytorch torchvision torchaudio -c pytorch

Once PyTorch is installed, we will install `torchvision <https://pypi.org/project/torchvision/>`_. In the terminal, use the command:

.. code-block:: bash
  
  >conda install torchvision -c pytorch

Now, install `Sklearn <https://scikit-learn.org/stable/index.html>`_:

.. code-block:: bash
  
  >pip install -U scikit-learn

After this is done, we will install our plotting tools `matplotlib <https://matplotlib.org>`_, and `seaborn <https://seaborn.pydata.org>`_!

.. code-block:: bash
  
  >conda install -c conda-forge matplotlib
  >conda install -c anaconda seaborn
  
This should be everything we need, so now we're good to go.  
