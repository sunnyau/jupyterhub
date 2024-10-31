# jupyterhub

JupyterHub is the best way to serve Jupyter notebook for multiple users.

https://jupyterhub.readthedocs.io/en/stable/


## set up

This project uses miniconda, a virtualenv and python package tool, to setup

- To install miniconda https://docs.anaconda.com/miniconda/#miniconda-latest-installer-links- after installing miniconda, we will create a virtual env called `jupyterhub`

- To activate this environment, use $ conda create --name jupyterhub
- To activate this environment, use $ conda activate jupyterhub
- To deactivate an active environment, use $ conda deactivate


https://jupyterhub.readthedocs.io/en/stable/tutorial/quickstart.html

```
conda install -c conda-forge jupyterhub  # installs jupyterhub and proxy
conda install jupyterlab notebook  # needed if running the notebook servers in the same environment

```
## Start the Hub server

To start the Hub server, run the command:

jupyterhub
Visit http://localhost:8000 in your browser, and sign in with your Unix credentials.

![Screenshot (31)](https://github.com/user-attachments/assets/33c29a6d-4b1a-45d1-86ef-c69241403dbf)


## useful conda commands

```
conda info --envs
conda remove -n my-env --all
conda env create -f environment.yaml -n my-env
conda env update -f environment.yaml
conda create --name jupyterhub
conda env export > environment.yaml
```


## Result




