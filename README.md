# Deep Learning 101
This repository contains jupyter notebooks for python, numpy, pytorch, CNN (Convolutional Neural Networks).

This is a collection of basic tutorials on Python, numpy, and pytorch tensor, and CNNs for MNIST dataset. I have borrowed many codes and notes from internet. I need to give back their credits some time later.

## Clone the repository
Go to a file folder at your local or remote cloud machine that you wish to play with this repository, and clone the repository from the github:
```
$ git clone https://github.com/hongbozhou/deep_learning_101.git
```
Note here `$` is a linux command prompt. There is no need to type it. Now you should have a folder named `deep_learning_101`. then `cd` to it.

## Set up virtual environment

To start, it's common practice to work on a project within a python virtual environment. I have been using python's builtin module `venv` for a long while. So I am going to stick to it here as an example to set up the virtual environment. But you are free to use any virtual environment that you feel comfortable with, such as `poetry`, etc. 
```
$ python -m venv venv_t
```
This will build a virtual environment `venv_t`. You only need to do it **once**.

If your linux Shell is `csh`, you may have to run the following command
```
$ source venv_t/bin/activate.csh
```
will activate this virtual environment. Otherwise, for other linux Shells, such as `bash` or plain `sh`, you may need to activate the environment with the following:
```
$ source venv_t/bin/activate
```

We generally collect other python package names into a file, such as `requirements.txt`. And we install those python packages to this virtual environment by running the following command:
```
$ pip install -r requirements.txt
```

## Jupyter notebooks
You can launch jupyterlab application with 
```
$ jupyter lab
```
or simply
```
$ jupyter-lab
```
whichever you prefer to. Jupyter's web interface should be launched in the default browser. If not, you can launch it by clicking the link that shows up on the terminal or by visiting http://localhost:8888 on your browser.You can now play with the jupyter notebooks.
