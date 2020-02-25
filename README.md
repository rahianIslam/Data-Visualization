# a2-numpy_pandas_vis
Exploring Numpy, Pandas, and visualization with Matplotlib, Pandas and Seaborn

Author: Rahian Islam

# Problem statement
The goal of this assignment is to recreate the analysis of the chicken and eggs data set presented in this video:
https://www.youtube.com/watch?v=j6ClFJhnG18

Watch the video. The first half is about visualization in general, the chicken and egg analysis starts at about 9:50. Note that the author uses R rather than Python.

The data set is unfortunately not available, so I have created one saved as `chicken.csv`. There are differences in the numbers, but the character should be the same.

The Jupyter notebook `chicken.ipynb` contains the skeleton to complete the exercise.
In _A. Analysis_, the different analysis steps are prepared for you. For all plots, you are asked to produce the plot first with `pandas.plot()` and then with seaborn. _Section B. Reflection_ asks you to think about both of these ways of plotting and which you prefer for what cases. Your opinion is what counts.
Section C. is optional

# What to do

Add your code and reflection to `chicken.ipynb` and commit your changes to your local git history and push to github as you progress.

Follow the style guide (below). Change author information in the `README.md` and notebook. Add instructions on how to run the notebook. No need for a screenshot this time.

If you get stuck with a visualization, please comment on what you are trying to do, and how to tried to resolve the issue in the corresponding cell in `chicken.ipynb`. 

Verify that all work in sections A and B is added and pushed to github.

# How to run this program
Running the program is pretty easy. Everything is done you just have to press run.

# Style guide
## Author
The first line of all scripts (.py files), and the first cell of all notebooks (.ipynb files) need to contain your first and last name, e.g. `# Author: Yves Pauchard`

## Variable, function and method naming
Use lower case for variable, function and method names. Underscore to separate composed words, e.g. `all_names = ['alice', 'bob']`

## Class naming
Start class names with a capital letter and use camel-case for composed words, e.g. `class GraduateStudent()`

## Comments
Focus on _why_ not _what_ comments, use `#` to start a comment

## Docstring
For each function/method, include a docstring with the following format:
```python
"""one line description, what does the function do?

name (type): description

returns: (type) description
"""
```

An example:
```python
def remove_middle(text):
    """Removes middle character of odd length text, a copy otherwise.

    text (str): any string

    return: (str) even length string
    """
```

Additionally, for classes provide a description and list of attributes:
```python
class Point:
    """Represents a point in 2-D space.

    attributes: x, y
    """
```

