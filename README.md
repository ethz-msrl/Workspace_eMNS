# Code for the analysis and determination of the workspace of electromagnetic navigation systems

## Description

TO DO


## Usage

### Installing dependencies

TO DO: installing libraries from tesla_core with apt?

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

Clone the repository in your home folder, if cloned to a different folder some of the script will not be able to export a pdf of the plot to the folder "~/tesla_jupyter/plot_pdf".

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