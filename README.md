# Cookiecutter for my Python analytics development projects

I've borrowed ideas and code from

* [the Cookiecutter Data Science homepage](http://drivendata.github.io/cookiecutter-data-science/)
* [Scientific Python Cookiecutter](https://github.com/NSLS-II/scientific-python-cookiecutter) 
 
Some of the big changes I made include:

* modified the folder structure to put a main package folder inside the `src/` folder,
* this modified folder structure necessitated some changes to `setup.py` to help it find the packages,
* included `src/input/` and `src/output` subdirectories since most of my dev projects use this structure.

### To start a new project, run:

    cookiecutter https://github.com/misken/cookiecutter-analytics-pydev


### The resulting directory structure

The directory structure of your new project looks like this. Of course,
you can always delete and add more folders as needed or desired. Leave the
src/ and main package subfolder of src/ alone unless you know what you
are doing (i.e. changes needed in setup.py).

```

```

## Contributing

Hopefully, as I do more dev projects I'll come up with ideas for improving this cookiecutter.
