# Patsy Design Info Persistence

_Personal Project for Quick Demo_


A quick and dirty example of how you can get around the limitation of patsy 0.4.1
which does NOT allow pickling of design_info object.


## Development:

### Git clone the repo to your workspace.

e.g. in Mac OSX terminal:

        $> git clone https://github.com/jonsedar/patsy_persistence.git
        $> cd patsy_persistence



### Setup a virtual environment for Python libraries

**NOTE:** using Python 3.5

Using Anaconda distro,

1. create a new virtual env, installing packages from env YAML file:


        $> conda env create --file conda_env_patsy_persistence.yml
        $> source activate patsy_persistence


