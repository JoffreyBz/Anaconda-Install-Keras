# Anaconda-Install-Keras
Use Anaconda to install Keras


Start with checking your python version in the anaconda prompt
**python --version**

Create a new/virtual environment using conda prompt (https://conda.io/docs/user-guide/tasks/manage-environments.html#activating-an-environment). 

**conda create -n dlenv python=3.5**

To be able to use Keras that is compatible with python 3.5.

Activate the virtual env: 
**activate dlenv**

Then execute the command: 
**conda install -c conda-forge keras**
This takes some decent time in my prompt.

Install Spyder in the virtual env: 
**conda install spyder python=3.5**

Run spyder in the virtual env: 
**spyder**


NOTE: **conda install *lib*** to install all other libraries you may need to use
