# Python introduction
Information for python.




## Installation
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
## Create slides
Interactive slides work in jupyter notebooks via
https://rise.readthedocs.io/en/maint-5.5/installation.html
```
pip install RISE
```
