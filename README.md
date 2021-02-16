# Python introduction
This repository provides a basic introduction to Python. An overview and introduction to the following concepts is provided.

- Variables and Types
- Lists
- Basic Operators
- Basic String Operations
- Conditions
- Loops
- Functions
- Dictionaries
- Modules and Packages

Good interactive python tutorials can be found online. 
For instance at `https://www.learnpython.org/ <https://www.learnpython.org/>`_.


## Presentation
For the course we require Python>3.7 and some additional dependencies.

Create a virtual environment
```
pip install virtualenv virtualenvwrapper
mkvirtualenv pyintro
(pyintro) pip install numpy scipy matplotlib pandas jupyter[notebook]
```

Use virtualenv as jupyter kernel
```
(pyintro) python -m ipykernel install --user --name=pyintro
```
### Create slides
Interactive slides work in jupyter notebooks via RISE
https://rise.readthedocs.io/en/maint-5.5/installation.html
```
pip install RISE
```
