# Installing Python, Jupyter Notebook, and clonnnig the tutorial from GitHub

If you decide to install `Python`, there are a number of ways and resources to do so. Here, we will explain how to install Python and Jupyter Notebook using __Conda__.

## Conda
[Conda](https://docs.conda.io/en/latest/) is package manager tool to help you install and update `Python` and any library you might need, keeping track of versions and conflicts. Not only for beginners, `conda` makes it easier and simpler to install and work with `Python` and other, always in development, libraries.

We will use __Miniconda__, which is a minimal installer of conda. This means that it will install `conda`, `Python`, the packages that they depend on, and only a small number of other packages. Nothing extra. The user will only install the packages (libraries) needed. This allows your `Python` installation to be tailored to your needs.


### Install Miniconda
- Download `Miniconda` [here](https://docs.conda.io/en/latest/miniconda.html). Choose your platform, and make sure to get Python 3.8. 
- Follow the Regular installation instructions for each platform, located [here](https://conda.io/projects/conda/en/latest/user-guide/install/index.html#regular-installation). (There are many sites with easier (or harder) to follow instructions, but this site is the most up-to-date one.)


### Install the necessary libraries and create a new 'environment'

- Additional libraries can be installed one by one, or as we will do here, using a list of libraries in a file named __environment.yml__. Download this file directly from [here](https://github.com/marisolgr/python_sat_tutorials/blob/main/environment.yml), or find it in the main folder of this tutorial if you cloned it from `Github` (instructions below). 
- Open an anaconda prompt:
  - Windows: From your start button, look for Anaconda, within that folder open 'Anaconda Prompt'. 
  - macOS: Open Launchpad, then open Terminal or iTerm.
  - Linux–CentOS: Open Applications - System Tools - Terminal.
  - Linux–Ubuntu: Open the Dash by clicking the upper left Ubuntu icon, then type “terminal”.
- In the anaconda window, type `conda list`. If Anaconda is installed and working, this will display a list of installed packages and their versions.
- In your anaconda prompt, type `conda env create -f environment.yml`. You may need to include the directory the environment.yml file was downloaded to.

### Run the tutorial

- In the anaconda prompt, type `conda activate tutorialenv` to load the created environment.
- Open a __Jupyter Notebook__ by typing `jupyter notebook` in the anaconda promt. This will open a __Jupyter Notebook__ `Dashboard`  in your browser. From there you can open the Chapter Notebooks by clicking at the file links. 

## Github

Downloading the content of a __GitGub__ repository to your local computer is referred as `cloning`. To clone this (or any repository):

- In a terminal type `git clone https://github.com/marisolgr/python_sat_tutorials`
- Or you can download it by going to the main page [here](https://github.com/marisolgr/python_sat_tutorials) and clicking on the green button named `Code`, at the top right of the file list. Then, click on __Download ZIP__ from the drop menu. Unzip it. 
- You might want to move this directory to a convenient place in your computer.
- From your __Jupyter Notebook__ `Dashboard`, navigate to the directory of the tutorial, and you'll see the Chapters files. 
