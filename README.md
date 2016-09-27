# CS510 CW 4

**Author(s):** _\<your name(s)\>_

[![Build Status](https://travis-ci.org/chapman-cs510-2016f/cw-05-YOURNAME.svg?branch=master)](https://travis-ci.org/chapman-cs510-2016f/cw-05-YOURNAME)

**Due date:** 2016/10/04

## Specification

**Note: Remember to use Python 3.**

Complete the following exercises, saving your solutions in the indicated files. For Python files that include test functions, GitHub will automatically run your tests with ```nosetests``` on every commit, indicating any failures via the Travis framework in the build status image above.

1. With your **new** group of **two**, work through the [Python object slides](http://slides.com/profdressel/python-objects-overview) carefully. Be sure to use ```ipython3``` in a terminal to test how things work. Discuss amongst yourselves anything that is new or unclear.
1. Together, carefully read through this [Example docstring style guide](http://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html) from Google. Google code may not be committed to the company repository without following this level of detail in docstrings. 
    * Open a Jupyter notebook: ```critique.ipynb```
    * Have one member of your group (the "reviewee") open the python code for their previous CW04. Have the other member (the "reviewer") constructively critique the code in a section of the Jupyter notebook. Use the following questions as a guideline: Is it clear how the code is organized? Is the code properly documented with both docstrings and supplementary comments according to industry standards? Can you follow the algorithm of the code, i.e., what it is doing, and how? Do you see any suggestions for how to improve the code? Discuss.
    * Repeat this exercise, but swapping roles of "reviewee" and "reviewer". In industry, code is typically reviewed in this fashion by fellow employees at regular intervals, for quality assurance. You are always liable for anything you commit to a repository. Moreover, constructive criticism is key: do not demean your colleagues, dismiss their feedback, or engage in any behavior that could be construed as promoting a toxic environment.
1. Create a python module ```cplane.py```. Import the module ```abscplane.py``` in the repository. Create a new class ```ComplexPlane``` that subclasses the abstract base class ```AbsComplexPlane```. Provide implementations for the requested methods. In particular, use a list of lists to represent the 2x2 grid needed to store the complex plane. Be sure to set all attributes properly during the ```__init__``` constuctor.
1. In a Jupyter notebook ```cw05-cplane.ipynb``` provide a demonstration of how your class works. Include a discussion about what an abstract base class helps a programmer do, and why it might be useful even though it doesn't do anything by itself. Be sure to switch the default kernel to Python 3 instead of the default Python 2 used by Sage.
1. After your notebook is complete, spell-checked, and professionally formatted properly, add and commit it to GitHub. Note that managing conflicts with Jupyter notebooks can be a pain, so I recommend having one person from your group be the official notebook editor, and having others in your group write code for the python modules in parallel.


## Assessment

Analyze in this section what you found useful about this assignment in your own words. Include any lingering questions or comments that you may have.

**CHANGEME**

## Honor Pledge

I pledge that all the work in this repository is my own with only the following exceptions:

* Content of starter files supplied by the instructor;
* Code borrowed from another source, documented with correct attribution in the code and summarized here.

Signed,

**YOURNAME**
