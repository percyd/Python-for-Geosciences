## Python for the Geosciences

Authors: Lisa Tauxe,  ltauxe@ucsd.edu, Hanna Asefaw, hasefaw@ucsd.edu,   
Brendan Cych, bcych@ucsd.edu, David Percy, percyd@pdx.edu, 

### Licensing: 

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg



### Computers in the Earth Sciences

Computers are essential to all modern Earth Science research.  We use them for compiling and analyzing data, preparing illustrations like maps or data plots, writing  manuscripts, building models, and so on.  In this class, you will learn to write computer programs with special applications useful to Earth Scientists.  We will learn Python, an object-oriented programming language, and use Jupyter notebooks to write our Python programs. Our focus is on using Python to access more dynamic data, as opposed to static data.

### Python

So, why learn Python?  Because it is:

- Flexible, freely available, cross platform
- Easier to learn than many other languages
- It has many numerical, statistical and visualization packages
- It is well supported and has lots of online documentation
- The name 'Python' refers to 'Monty Python' - not the snake - and many examples in the Python documentation use jokes from the old Monty Python skits.  If you have never heard of Monty Python, look it up on youtube; you are in for a treat. 

Which Python?  
- Python underwent a transition from 2.7 to 3.  The notebooks in this class, apart from a few exceptions, are compatible with both but they have only been tested on Python 3, so that is what you should be using.   
- If you decide to use a personal computer, we recommend that you install the most recent version of Anaconda python for your operating system: 
https://www.anaconda.com/download/
you will also need a few extra packages (cartopy, version 0.17.0,  geoplots, geopandas and a few others) which can be installed with little hassle.  

### Jupyter notebooks

This course is entirely structured around a special programming environment called [Jupyter notebooks](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html). A Jupyter notebook is a development environment where you can write, debug, and execute your programs.  

Clone or download this repository and launch the Jupyter notebook environment. 

To do this, you will need to discover the hidden secret of your computer, the _Terminal window_ (or Anaconda Prompt on a PC).  This little window provides a _command line interface_ in which you can type commands to the operating system. You  can  find the terminal window through the program **Terminal** on a Mac  by typing terminal.app into the search icon.  If you double click on it, it will open a terminal window.  To find it on a PC search for the program anaconda

Once you have launched the jupyter notebook browser, navigate to your course directory and open Lecture_01.ipynb


<!-- #region -->
### [Lecture 1](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_01.ipynb)


- Learn to find your command line interface.
- Learn how to launch a Jupyter notebook from the command line interface
- Learn basic notebook anatomy.
- Learn some basic python operating system commands 
- Learn about the concept of **PATH**
- Turn in your first practice problem notebook.  

### [Lecture 2](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_02.ipynb)

- Learn  about variables
- Learn about operations

### [Lecture 3](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_03.ipynb)

- Learn about collections of variables: data structures 

- Learn about _objects_ 
- Learn about _methods_ which allow you to do things to _objects_

### [Lecture 4](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_04.ipynb)

- Learn more about another useful data structure, **dictionaries** and some of their **methods**
- Introduce special Python code blocks
- Learn about "for" loops, "while" loops and "if" blocks

### [Lecture 5](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_05.ipynb)

- Learn about functions
- Discover the joys of modules 

### [Lecture 6](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_06.ipynb)

- get a first peek at the very useful Python packages called **NumPy** and **matplotlib**

### [Lecture 7](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_07.ipynb)

- Learn more about **NumPy** and **matplotlib**
- Learn more about **NumPy** arrays.  
 

### [Lecture 8](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_08.ipynb)

-  more about **matplotlib**:  adding notes and saving images
-  about DataFrames and Series, two new _data structures_, that are part of the **Pandas** package 
-  some basic filtering tricks with **Pandas**
-  how to read in and save data files with **Pandas**

### [Lecture 9](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_09.ipynb)

- Learn how to filter data with Pandas
- Write a program to calculate the great circle distances between two known points. 
- Learn how to generate  formatted strings for output.

### [Lecture 10](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_10.ipynb)

- Exploring data using pandas

### [Lecture 11](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_11.ipynb)

- Processing data with pandas

### [Lecture 12](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_12.ipynb)

- Tricks with pandas
- Filtering 
- concatentating and merging dataframes

### [Lecture 15](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_15.ipynb)

- Learn some basic statisics - samples versus populations and empirical versus theorectical distributions.
- Learn to calculate _central tendencies_, _spreads_. 
- Learn about _significant figures_ and more about formatting output. 
- Learn some useful functions in **NumPy** and **SciPy** for simulating distributions and calculating statistics.

### [Lecture 17](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_17.ipynb)

- Learn how to use the **seaborn** package to produce beautiful plots
- Learn about kernel density estimates
- Learn appropriate ways of representing different types of data

### [Lecture 20](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_20.ipynb)

- Learn about geoplot and geopandas
- Learn a bit about coordinate systems (UTM versus WGS84, as examples)
- Learn something about Hawaiian volcanism

### [Lecture 24](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_24.ipynb)

- Find out about Machine Learning
- Learn about using the **scikit-learn** python package for clustering analysis.
- Apply clustering analysis to Earth Science problems

### [Lecture 25](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_25.ipynb)

- Learn how to use satellite imagery to understand land usage.
- Learn how to use patches in matplotlib.
- Learn about using the **scikit-learn** python package to classify data.


### [Lecture 26](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_26.ipynb)

- Learn about 3D plots of points and surfaces
- Show some examples with subduction zone earthquakes and isotopic systems

### [Lecture 27](https://nbviewer.jupyter.org/github/percyd/Python-for-Earth-Science-Students/blob/master/Lecture_27.ipynb)

- Take a look at data with respect to time (time series)
- Learn a bit about time series analysis. 

<!-- #endregion -->

```python

```
