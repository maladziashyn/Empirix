# CHECKLIST

## Install Python, latest

`$ sudo add-apt-repository ppa:deadsnakes/ppa`

`$ sudo apt update`

`$ sudo apt install python3.12`

## Install pip

[Read more](https://pip.pypa.io/en/stable/installation/)

## Install venv

`$ sudo apt install python3.12-venv`

Create venv in current directory:

`$ python3.12 -m venv .`

### Activate venv

Linux:

`$ source bin/activate`

Windows:

`$ Scripts/activate`

### Deactivate venv

`$ deactivate`

## Install Jupyter lab / notebook

[Read more](https://jupyter.org/install)

## Add Jupyter to venv emp-py312

1) Activate venv: `$ source your-venv/bin/activate`

2) Install jupyter in the virtualenv: `(your-venv)$ pip install jupyter`

3) Add the virtualenv as a jupyter kernel: `(your-venv)$ ipython kernel install --name "local-venv" --user`

To remove:

`$ jupyter kernelspec list  # find trash-venv there`

`$ jupyter kernelspec uninstall trash-venv`

[Sources](https://queirozf.com/entries/jupyter-kernels-how-to-add-change-remove
Add & remove venv for Jupyter: https://pythoninoffice.com/virtual-environment-and-jupyter-notebook/)

