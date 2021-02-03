# UoU FLORIS demo

Nicholas Hamilton
nicholas.hamilton@nrel.gov

Project start date: February 3, 2021

## Get Python
I'd recommend using:
 - brew (mac, https://docs.python-guide.org/starting/install3/osx/) 
 - Python direct installation (https://www.python.org/)
 - Anaconda https://www.anaconda.com/

## Setup Virtual Environment
```
$ pip install virtualenv
$ pip install virtualenvwrapper

$ export WORKON_HOME=$HOME/.virtualenvs   # Optional
$ export PROJECT_HOME=$HOME/projects      # Optional
$ source /usr/local/bin/virtualenvwrapper.sh

$ mkvirtualenv wakemod
$ workon <your env name>
$ python -m ipykernel install --user --name=<your env name>
```

## Get FLORIS
```
$ cd <code repo dir>
$ git clone https://github.com/NREL/floris.git
$ pip install –e floris
```

## Setup project directory
```
$ cd <working directory>
$ git clone
```
## Examples:

Lots of examples have been developed as part of the FLORIS repository. 
```
$ cd <code repo dir>/floris/examples/
```

There are also some example jupyter notebooks in this repo for you to use and build on for your own work.
```
$ cd <working directory>/UoU_FLORIS_demo/notebooks/
```



