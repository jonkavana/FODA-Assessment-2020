# FODA-Assessment-2020
Assessment work for the Fundamentals of Data Analysis Course - GMIT 2020

In the information provided below is an assignment as part of the Fundamentals of Data Analysis module. Each task is run independently and will require seperate breakdowns in order to fully understand what is being requested and to ensure that the output mataches that expectation. The goal of this file is to provide a succinct overview, not just of the tasks, but the material required to successfully complete the tasks.


## Overview of the Assessment
There is going to be four parts to this assessment, each one uploaded throughout the course of the module. There needs to be one jupyter notebook established to centrally combine these four tasks and the research associated.


## User Requirements
Each user needs to have the following available to them in order to progress from start to finish for this exercise. 

1) Laptop needs to be available at all times. 
2) Python needs to be installed on the laptop
3) Aceess to and understanding of Jupyter Notebook
4) Understanding and implementation of libraries such as, but not limited to: Numpy, MatplotLib and SciPy
5) GitHub account
6) Visual Stuido Code
7) Cmder console emulator


### Part 1 - Counts
October 5th, 2020:
Write a Python function called counts that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values.

    So, the input ['A', 'A', 'B', 'C', 'A'] should have output {'A': 3, 'B': 1, 'C': 1} .

Your code should not depend on any module from the standard library or otherwise. You should research the task first and include a description with references of your algorithm in the notebook.

Addendum via Moodle: with Python, anything built-in that can be used without an import statement can be used.

#### Breakdown of the task
- Create a function called counts.
- Needs to be the end user who inputs the data for eventual summation.
- This output will then need to be returned as a dictionary of 'unique items in the list as keys' 
    - This is the relevant link to dictionary as a storer of key-value pairings
- Working Assumption: i think this means take the data that is input and do with it as you see fit i.e., count the number of times a letter is produced.
- Output of this list needs to be counted, as per the example.


### Part 2 - DiceRolls
November 2nd, 2020:
Write a Python function called dicerolls that simulates rolling dice. Your function should take two parameters:
- The number of dice k and
- The number of times to roll the dice n. 

The function should simulate randomly rolling k dice n times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. 

    Calling the function as diceroll(k=2, n=1000) return a dictionary like: {2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36} 

You can use any module from the Python standard library you wish and you should include a description with references of your algorithm in the notebook.

#### Breakdown of the task
- Create a function called dicerolls
- Set up the function so that it takes two arguements
- Need to be able to implement a for loop to run through the programe
- Need to be able to find a way of adding two seperate arrays
- Result is not based on two die, but a number of die dictated by the user
- Return needs to be in a dictionary.


### Part 3 - Tossing a coin simulation
November 16th, 2020:
The numpy.random.binomial function can be used to simulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if a coin is flipped many times then the number of heads is well approximated by a bell-shaped curve.

For instance, if we flip a coin 100 times in a row the chance of getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively low, and the chances of getting any other number of heads decreases as you move away from 50 in either direction towards 0 or 100.

Write some python code that simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve. You should explain your work in a Markdown cell above the code

#### Breakdown of the task
- Complete review of the distributions section of Numpy.random package
- Setup of a programme called Toss to simulate the tossing of a coin 
- Implementation of size parameter to replicate the above to the requested amount of 1,000
- Implementation of MatplotLib library to visually display the output.
- Explanation of code throughout as well as an overview at start of task.


### Part 4 - Simpsons Paradox
November 30th, 2020: Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined into one big data set. Use numpy to create four data sets, each with an x array and a corresponding y array, to demonstrate Simpson’s paradox. You might create your x arrays using numpy.linspace and create the y array for each x using notation like y = a * x + b where you choose the a and b for each x , y pair to demonstrate the paradox. You might see the Wikipedia page for Simpson’s paradox for inspiration.

#### Breakdown of the task
- Complete review of the lecture material to understand the UC Berkley Bias Paper
- Research of Simpsons Paradox for further understanding and context
- Complete review of the Numpy.Linspace package and associated packages
- Implementation of the above to replicate data to:
    - Creation of four seperate data sets of with X & Y components
    - Couple together the first two data sets, ensuring that the number of samples generated are equal as per the documentation guidance in the Jupyter file.
    - Repeat for the third and fourth set of data sets. 
    - Perform a direct comparison between the collected datasets, to display the disparity
    - Perform an exploded view to display there is a case of marginal and partial association viewable. 
- Results to be displayed graphically on the jupyter notebook 


## Bibliogrpahy

LearnPython - Function
https://www.learnpython.org/en/Functions


Able.bio
https://able.bio/rhett/check-if-a-key-exists-in-a-python-dictionary--73iajoz#:~:text=To%20simply%20check%20if%20a,')%20%23%20Dogs%20found!&text=A%20dictionary%20can%20be%20a,counting%20the%20occurrence%20of%20items.

Stack Overflow
https://stackoverflow.com/questions/45069108/use-list-as-function-definition-parameters-in-python

Old Refernece guide for Integers: 
https://numpy.org/doc/stable/reference/random/generated/numpy.random.randint.html#numpy.random.randint

  
Python - The Python Standard Library, retrieved on October 12th 2020 
https://docs.python.org/3/library/

RealPython - How to Iterate Through a Dictionary in Python, retrieved on October 12th 2020
https://realpython.com/iterate-through-dictionary-python/

LearnPython - Function, retrieved on October 14th 2020
https://www.learnpython.org/en/Functions

Able.bio, retrieved on October 14th 2020
https://able.bio/rhett/check-if-a-key-exists-in-a-python-dictionary--73iajoz#

W3Schools - For Loops Explanation, retrieved on October 14th 2020
https://www.w3schools.com/python/python_for_loops.asp  

Numpy - Generate a permutation - retrieved on 14th November 2020
https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.permutation.html?highlight=numpy%20random%20permutation#numpy.random.Generator.permutation

Stack Overflow - Function Parameters - retrieved on 14th November 2020
https://stackoverflow.com/questions/45069108/use-list-as-function-definition-parameters-in-python

Numpy - Old Refernece guide for Integers - retrieved on 14th November 2020
https://numpy.org/doc/stable/reference/random/generated/numpy.random.randint.html#numpy.random.randint

W3Schools - Append reference material - retrieved on 16th November 2020
https://www.w3schools.com/python/python_arrays.asp

Geeks for geeks - Append reference material - retrieved on 16th November 2020
https://www.geeksforgeeks.org/append-extend-python/

Numpy - Generator for integers - retrieved on 16th November 2020
https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.integers.html#numpy.random.Generator.integers

SciPy Array - retrieved on 16th November 2020
https://stackoverflow.com/questions/49881570/python-dictionaries-appending-arrays-to-a-dictionary-for-a-specific-key

   
SciKit - An introduciton to Machine Learning with Scikit-learn - Retrieved on 30th November 2020
https://scikit-learn.org/stable/tutorial/basic/tutorial.html

Numpy - Numpy.equal - Retrieved on 30th November 2020
https://numpy.org/doc/stable/reference/generated/numpy.equal.html

Numpy - Numpy Binomial - Retrieved on 30th November 2020
https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.binomial.html#numpy.random.Generator.binomial

Statology - How to make a Bell Curve in Python - Retrieved on 6th December 2020
https://www.statology.org/bell-curve-python/

Python & R Tips - Simulating Coin Toss Experiment in Python with NumPy - Retrieved on 30th November 2020
https://cmdlinetips.com/2018/12/simulating-coin-toss-experiment-with-binomial-random-numbers-using-numpy/

MatPlotib - PyPlot Tutorial - Retrieved on 6th December 2020
https://matplotlib.org/tutorials/introductory/pyplot.html

MatPlotib - Histogram Overview - Retrieved on 6th December 2020
https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.hist.html

SciPy - scipy.stats.binom - Retrieved on 12th December 2020
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.binom.html#scipy.stats.binom

SciPy - scipy.stats.norm - Retrieved on 12th December 2020
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.norm.html

  
Numpy Linspace - Retrieved on 20th December 2020
https://numpy.org/doc/stable/reference/generated/numpy.linspace.html

KDNuggets - Retrieved on 10th December 2020
https://www.kdnuggets.com/2020/09/simpsons-paradox.html

Towards Science - Retrieved on 10th December 2020
https://towardsdatascience.com/solving-simpsons-paradox-e85433c68d03

MinutePhysics - Retrieved on 13th December 2020
https://www.youtube.com/watch?v=ebEkn-BiW5k

Britannica - Retrieved on 10th December 2020
https://www.britannica.com/topic/Simpsons-paradox

Simpsosn Paradox - Retrieved on 10th December 2020
https://en.wikipedia.org/wiki/Simpson%27s_paradox#cite_note-16

Towards Science - Retrieved on 12th December 2020
https://towardsdatascience.com/simpsons-paradox-how-to-prove-two-opposite-arguments-using-one-dataset-1c9c917f5ff9

US National library of medicine - Retrieved on 20th December 2020
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1339981/

Towards Science - What is Simpson’s Paradox? - Retrieved on 20th December 2020
https://towardsdatascience.com/what-is-simpsons-paradox-4a53cd4e9ee2

Medium.com - Markdown File - Retrieved on 19th December 2020
https://medium.com/markdown-monster-blog/getting-images-into-markdown-documents-and-weblog-posts-with-markdown-monster-9ec6f353d8ec

Kite.com - Line of best fit - retrieved on 20th of December
https://www.kite.com/python/answers/how-to-plot-a-line-of-best-fit-in-python