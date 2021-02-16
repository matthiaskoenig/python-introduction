# Python introduction
Information for python.




## Installation
For the course we require Python>3.7 and some additional dependencies.

Create a virtual environment
```
pip install virtualenv virtualenvwrapper
mkvirtualenv pyintro
(pyintro) pip install numpy scipy matplotlib pandas jupyterlab
```

Use virtualenv as jupyter kernel
```
(pyintro) python -m ipykernel install --user --name=pyintro
```
## Create slides
```
jupyter nbconvert 01_python_introduction.ipynb --to slides
```

