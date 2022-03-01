# Analysis and determination of the workspace of electromagnetic navigation systems

## Description

This is the companion code to the submission "On the Workspace and Evaluation of Electromagnetic Navigation Systems", Boehler Q., Gervasoni S. Charreyron S.L., Chautems C., Nelson B.J.
The repository is composed of Jupyter notebooks that can be used to reproduce the results presented in the publication, and to further analyse other electromagnetic manipulation systems.

## Using code in pre-installed environment

The code is available in a pre-installed environment on [CodeOcean](https://doi.org/10.24433/CO.2090933.v1).

## Usage

### Compatibility

This code was developped and tested on Linux O.S. (Ubuntu 20.04) and with Python 3.8.

### Installing dependencies

#### Libary for utilies functions import

The functions used in the notebooks are defined in ```utilities.ipynb``` and imported as ```from ipynb.fs.defs.utilities import *```.
This requires the following package:

``` bash
pip3 install ipynb --upgrade
```

#### Libraries for magnetic models

Install libraries for magnetic manpipulation:

``` bash
pip install mag-manip
```

#### Libraries for graphics and plotting

Install [Matplotlib and MPL_toolkits](https://matplotlib.org/stable/users/installing.html).

#### Libraries for maths and computation

Install:
* [NumPy](https://numpy.org/install/)
* [PyYAML](https://pypi.org/project/PyYAML/)
* [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)
* [SciPy](https://pypi.org/project/scipy/)

#### Libraries for interval analysis

Install [PyInterval](https://pyinterval.readthedocs.io/en/latest/index.html) and the [python binding](https://www.ensta-bretagne.fr/desrochers/pyibex/docs/pyibex/installation.html) of [ibex](http://www.ibex-lib.org/).

### Installing Jupyter notebook

The Jupyter Notebook is an open source web application that you can use to create and share documents that contain live code, equations, visualizations, and text.
It is convenient to use Jupyter as an interactive python editor where you can run the code directely from a web browser and create some plots.
Install pip and the Python header files, which are used by some of Jupyter’s dependencies:

``` bash
sudo apt install python3-pip python3-dev
pip install jupyter
pip install jupyterlab
pip install ipywidgets
```

### Clone the Repository

Clone the repository in your home folder

``` bash
cd ~
git clone git@github.com:ethz-msrl/Workspace_eMNS.git
```
or download the source code and place it in your home folder.

### Launching Jupyter Lab 

To launch Jupyter open a terminal and launch jupyter notebook. This will open a webbrowser window.

``` bash
jupyter lab
```

### Launching Jupyter Notebook (alternative to Jupyter lab)

To launch Jupyter open a terminal and launch jupyter notebook. This will open a webbrowser window.

``` bash
jupyter notebook
```
