# Analysis and determination of the workspace of electromagnetic navigation systems

## Description

This is the companion code to the submission "On the Workspace of Electromagnetic Navigation Systems", Boehler Q., Gervasoni S. Charreyron S.L., Chautems C., Nelson B.J.
The repository is composed of Jupyter notebooks that can be used to reproduce the results presented in the publication, and to further analyse other electromagnetic manipulation systems.

## Usage

### Installing dependencies

#### Libraries for magnetic manipulation

TO DO: installing libraries from tesla_core with apt?

#### Libraries for interval analysis

Install [PyInterval](https://pyinterval.readthedocs.io/en/latest/index.html) and the [python binding](https://benensta.github.io/pyIbex/) of [ibex](http://www.ibex-lib.org/).

### Installing Jupyter notebook

The Jupyter Notebook is an open source web application that you can use to create and share documents that contain live code, equations, visualizations, and text.
It is convenient to use Jupyter as an interactive python editor where you can run the code directely from a web browser and create some plots.
Install pip and the Python header files, which are used by some of Jupyter’s dependencies:

```
sudo apt install python3-pip python3-dev
pip install jupyter
pip install jupyterlab
```

### Clone the Repository

Clone the repository in your home folder

```
cd ~
git clone git@github.com:ethz-msrl/Workspace_eMNS.git
```
or download the source code and place it in your home folder.

### Launching Jupyter Lab 

To launch Jupyter open a terminal and launch jupyter notebook. This will open a webbrowser window.

```
jupyter lab
```

### Launching Jupyter Notebook (alternative to Jupyter lab)

To launch Jupyter open a terminal and launch jupyter notebook. This will open a webbrowser window.

```
jupyter notebook
```