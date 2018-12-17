# Anaconda-Install-Keras
Use Anaconda to install Keras

1/Start with checking your python version in the anaconda prompt. Dec 2018 keras is not working with python 3.7
**python --version**

2/Create a new/virtual environment using conda prompt (https://conda.io/docs/user-guide/tasks/manage-environments.html#activating-an-environment) To be able to use Keras that is compatible with python 3.5.

**conda create -n dlenv python=3.5**

3/Activate the virtual env: 
**activate dlenv**

4/Execute the command: 
**conda install -c conda-forge keras**
This takes some decent time in my prompt.

5/Install Spyder in the virtual env: 
**conda install spyder python=3.5**

5b/NOTE: **conda install *lib*** to install all other libraries you may need to use

6/Run spyder in the virtual env: 
**spyder*
