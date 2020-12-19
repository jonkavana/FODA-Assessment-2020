# FODA-Assessment-2020
Assessment work for the Fundamentals of Data Analysis Course - GMIT 2020


# Overview of the Course Assessment
There is going to be four parts to this assessment, each one uploaded throughout the course of the module. 


# User Requirements
Each user needs to have the following available to them in order to progress from start to finish for this exercise. 

## Material
1) Laptptop needs to be available at all times. 
2) Python needs to be installed on the laptop
3) Standard Python Library to be used
4) Aceess to and understanding of Jupyter Notebook


## Part 1 - Counts
October 5th, 2020: Write a Python function called counts that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values. So, the input ['A', 'A', 'B', 'C', 'A'] should have output {'A': 3, 'B': 1, 'C': 1} . Your code should not depend on any module from the standard library1 or otherwise. You should research the task first and include a description with references of your algorithm in the notebook.

Addendum via Moodle: with Python, anything built-in that can be used without an import statement can be used.

### Breakdown of the task
- Create a function called counts.
- Needs to be the end user who inputs the data.
- This will then need to be returned a dictionary of 'unique items as keys' - needs a better understanding of this, perhaps context dependent.
- Assumption: i think this means take the data that is input and do with it as you see fit i.e., count the number of times a letter is produced.
- Output of this list needs to be counted, as per the example.


## Part 2 - DiceRolls
November 2nd, 2020: Write a Python function called dicerolls that simulates rolling dice. Your function should take two parameters: the number of dice k and the number of times to roll the dice n. The function should simulate randomly rolling k dice n times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. So, calling the function as diceroll(k=2, n=1000) should return a dictionary like: {2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36} You can use any module from the Python standard library you wish and you should include a description with references of your algorithm in the notebook.

### Breakdown of the task

## Part 3 - Coin Toss
November 16th, 2020: The numpy.random.binomial function can be used to simulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if a coin is flipped many times then the number of heads is well approximated by a bell-shaped curve. For instance, if we flip a coin 100 times in a row the chance of getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively low, and the chances of getting any other number of heads decreases as you move away from 50 in either direction towards 0 or 100. Write some python code that simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve. You should explain your work in a Markdown cell above the code

### Breakdown of the task

## Part 4 - Simpsons Paradox
November 30th, 2020: Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined into one big data set. Use numpy to create four data sets, each with an x array and a corresponding y array, to demonstrate Simpson’s paradox. You might create your x arrays using numpy.linspace and create the y array for each x using notation like y = a * x + b where you choose the a and b for each x , y pair to demonstrate the paradox. You might see the Wikipedia page for Simpson’s paradox for inspiration.

### Breakdown of the task

# Bibliogrpahy

[1] The python Standard library: https://docs.python.org/3/library/