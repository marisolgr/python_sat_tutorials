If you decide to install `Python`, there are a number of ways and resources to do so. In here, we will explain how to install Python and Jupyterlab using __Conda__, a package manager.

## Conda
[Conda](https://docs.conda.io/en/latest/) is a tool that help you install and update Python and any library you might need. Although not only for beginners, conda makes like easier and simplier to install module-built `Python`.

We will use __Miniconda__ which is a minimal installer of conda. This means that it install conda, `Python`, packages that they depend on, and only a small number of other packages. The user will install only the packages (libraries) needed. This allows your Python installation to be tailored to your needs. 


### Install Miniconda
Download miniconda from [here](https://docs.conda.io/en/latest/miniconda.html). Choose your platform, and make sure to get Python 3.8. Follow the Regular installation instructions for each platform are located [here](https://conda.io/projects/conda/en/latest/user-guide/install/index.html#regular-installation). (There are many sites with easier (or harder) to follow instructrions, but this site is the most up to date one.)

Additional libraries can be install one by one, or as we will use here, using a list of libraries in a file named __environment.yml__. Download this file from directly from [here](https://github.com/marisolgr/python_sat_tutorials/blob/main/environment.yml), or find it in the main folder of this tutorial if you cloned it from Github (instructions below). 

### Install the necessary libraries and create a new 'environement'

Start by opening an anaconda promt:
- Windows: From your start button, look for Anaconda, within that folder open 'Anaconda Prompt'. You are done, skip to next section on installing libraries.
- macOS: Open Launchpad, then open Terminal or iTerm.
- Linux–CentOS: Open Applications - System Tools - Terminal.
- Linux–Ubuntu: Open the Dash by clicking the upper left Ubuntu icon, then type “terminal”.

In the anaconda window type `conda list`. If Anaconda is installed and working, this will display a list of installed packages and their versions.

At your anaconda prompt, type `conda env create -f environment.yml`. You may need to include the directory the environment.yml file was downloaded to.

Once finished, let's open a __JupyterLab__, as a test. At the anaconda prompt type `conda activate tutorialenv` then type `jupyter lab`. This will open a jupyter lab in your browser. From there you can open notebooks and run them. 

## Github

To download the content of a __GitGub__ repository into your local computer is referred to 'cloning'. To clone this (or any repository):

- In a terminal type `git clone https://github.com/marisolgr/python_sat_tutorials`
- Or you can download it by going to the main page [here](https://github.com/marisolgr/python_sat_tutorials) and clicking on the green button named `Code`, at the top right of the file list. Then, click on __Download ZIP__ from the drop menu. 