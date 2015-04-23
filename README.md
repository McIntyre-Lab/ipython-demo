# ipython-demo

A set of IPython Notebooks to demonstrate some of the features available. 

## Installation

To get started you need to have python and IPython installed. For simplicity
I suggest [Enthought Canopy](https://store.enthought.com/#canopy-academic)
because it has a nice package manager and installs a lot of useful scientific
packages by default. They have a free academic license if you sign-up with an
EDU (just follow the above link). Canopy is available for Windows, OSX, and
Linux. Once installed make sure to open the package manager and install all
updates. Also make sure to install `mpld3` if you want to follow all of the
tutorial.

If you are on linux and don't want to install Canopy then install the following
from your package manager.

>>> $ sudo apt-get install python-numpy python-scipy python-pandas python-pip ipython ipython-qtconsole ipython-notebook

Then make sure to update ipython to the latest version.

>>> $ pip install ipython[all] --upgrade --user

## Running IPython notebook

The easiest way to get IPython notebook running is to open a command prompt or terminal and type:

>>> $ ipython notebook

This will start a web server running the IPython notebook. You can then navigate your directory structure through the notebook. When done simply close the web browser and type Ctrl-C in the command prompt/terminal to stop the web server.

## Go Through Demos

Download this [repository](https://github.com/McIntyre-Lab/ipython-demo/archive/master.zip) and unzip it. Within IPython notebook navigate to the directory. Then go through the tutorials in this order.

* set_up_ipython_notebook.ipynb ([nbview](http://nbviewer.ipython.org/github/McIntyre-Lab/ipython-demo/blob/master/set_up_ipython_notebook.ipynb))
* interactive_plotting.ipynb ([nbview](http://nbviewer.ipython.org/github/McIntyre-Lab/ipython-demo/blob/master/interactive_plotting.ipynb))
* r_inside_ipython_pt1.ipynb ([nbview](http://nbviewer.ipython.org/github/McIntyre-Lab/ipython-demo/blob/master/r_inside_ipython_pt1.ipynb))
