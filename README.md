# Deep Learning 101
This repository contains jupyter notebooks for python, numpy, pytorch, cnn

This is a collection of basic tutorials on Python, numpy, and pytorch tensor, and CNN (Convolutional Neural Network) for MNIST dataset. I have borrowed many codes and notes from internet. I need to find sometime to give back their credits.

## Virtual environment

To start, it's common practice to work on a project within a python virtual environment. I have been using python's builtin module *venv* for a long while. So I am going to stick to it here as an example to set up the virtual environment. But you are free to use any virtual environment that you feel comfortable with, such as *poetry*, etc. 
```
% python -m venv venv_t
```
This will build a virtual environment *venv_t*. Note here `$` is a linux command prompt. There is no need to type it. 

Running the following command
```
% source venv_t/bin/activate
```
will activate this virtual environment.

If we need some other python packages, we can collect them into a file, such as `requirements.txt`. And install those python packages to this virtual environment by running the following command:
```
% pip install -r requirements.txt
```

## Jupyter notebook
You can launch jupyter notebook with 
```
% jupyter lab
```
or simply
```
% jupyterlab
```
whichever you prefer to. Jupyter's web interface should be launched in the default browser. If not, you can launch it by clicking the link that shows up on the terminal or by visiting http://localhost:8888 on your browser.You can now play with the jupyter notebooks.