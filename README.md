# MoCoVisualizer

**Set Up Instructions**

* Run a few commands to install some things that will be needed to make the widgets run in Jupyter Lab.

> conda install -c conda-forge ipywidgets  
> conda install nodejs  
> jupyter labextension install @jupyter-widgets/jupyterlab-manager  
> conda install nb_conda_kernels  

* Make a folder for Python stuff and change directory so you are in it.

> cd Documents
> mkdir Python
> cd Python

* Clone this repository.

> git clone https://github.com/bcminch/MoCoVisualizer.git

* Change directory to enter the new folder.

> cd MoCoVisualizer

* Create an environment for this project. 

> conda create --name "MoCoVisualizer" --file requirements.txt

* Launch Jupyter Lab to test out notebook

> jupyter lab