# Basic Python data science environment using Vagrant

## About the author

This repository was created by [MSc Benjamin Tovar Cisneros](https://www.linkedin.com/in/benjamintovarcis/) on November 2015.

## Dependencies: 

### Vagrant

Download version >= 1.7.x | 
[Download it here](https://www.vagrantup.com/downloads.html)

### VirtualBox

Download version >= 5.x | 
[Download it here](https://www.virtualbox.org/wiki/Downloads)

## This machine includes:

### Machine environment

- Ubuntu 12.04 amd64

### Python packages

- IPython
- SciKit-Learn
- Jupyter
- NumPy
- SciPy
- Pandas

## Setting the machine UP!

+ Install dependencies (Vagrant and VirtualBox)
+ Clone this repository
+ Open a terminal and type: 
    - `vagrant up`
+ Access the machine with: 
    - `vagrant ssh`
+ To kill the machine type: 
    - `vagrant halt`
+ To **delete** the machine type:
    - `vagrant destroy`

## NOTES:

- I always start my projects using R because I find it much easier to set up a *playground* to test hypothesis, plot awesome `ggplot` charts and give insights. 
- That said, I usually (and would recommend) use Python for *production* purposes, so that is why I did not include any Python ploting library while setting the Python environment.


