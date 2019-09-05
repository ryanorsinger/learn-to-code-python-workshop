# Intro to Python for Data Science

## Why are we here?
1. Intro to the Codeup experience
2. Overview of Data Science
3. Intro to programming in Python

## Why Codeup?
1. Focus on student outcomes
2. Placement services and quality of network
3. Immersion works. Full-time, live, in-person instruction for 5 months works.

### What is Data Science?
- Interdisciplinary applied science at the intersection of programming, statistics, and business
- The application of the scientific method of hypothesis-experiment-analyze-repeat to analyze and infer outcomes from data. 
- A broad description of approaches ranging from business analysis and visualizations to machine learning and deep neural network analysis.
- An increasingly accessible field

### What *isn't* Data Science?
- Only statistics or only mathematics: let the computer compute and the people think
- Magic or inaccessible

### Isn't data science just statistics?
- "Future of Data Analysis", Tukey 1962, `https://projecteuclid.org/euclid.aoms/1177704711`
- "50 Years of Data Science" by Donoho, `https://courses.csail.mit.edu/18.337/2015/docs/50YearsDataScience.pdf`

### 3 keys to success that students get from Codeup
1. In addition to learning data science, students learn how to continue learning data science into the future
2. How to form and ask effective questions, find your own answers, and collaborate in the face of uncertainty (how to get really good at googling stuff and collaborating with people)
3. How to debug and troubleshoot using the scientific method

### 5 Ways to get the most out of this workshop
1. Engage with the material, engage with others
2. Ask questions
3. What you get out of this is a function of what you put into it
4. Treat each other with excellence
5. Try things out! Run code! Experiment with the material!

### 6 things you will get from today's workshop
1. An introduction to the Codeup experience
2. Introduction to Python fundamentals
3. Explanation of some mathematical notation in terms of Python and English
4. Intro to popular Python data science libraries and methods
5. Instructional materials and your own copies of the prepared learning environments
6. Time to practice with the material including guidance and support on exercises

### What we will *not* cover today
- Excel, R, SAS, SPSS, or other statistical analysis tools
- Everything you need to know about Python or statistics
- 5 months worth of practice, exercises, training, and mentoring
- Perceptrons, neural networks, and deep learning (too much for a 4 hour intro)

### The five questions Data Science can answer

1. How many or how much of something? What will sales be next year?
2. Which category does this thing belong to: is this A or B?
3. What groups? Does grouping things provide additional insight? Who are our best customers?
4. Is this weird? Anomaly detection like looking for fraudulent transactions
5. What should we do next? Infer likely outcomes

### Some Data Science Methodologies

- Regression - predict housing prices

- Classification - predict customers who will churn

- Clustering - identify physical neighborhoods, identify similar species

- Time series analysis - forecast revenue, predict store item demand

- Anomaly Detection - detect fraudulent transactions, account takeovers 

- NLP - Siri, sentiment analysis, twitter bots, customer feedback

- Graph Analysis - social networks, web analytics, page rank

- Recommender Systems - netflix, amazon shopping

- Neural Networks / Deep Learning - image recognition, face recognition

## Intro to Programming in Python

Python is a high-level, dynamic, interpreted programming language that has gained a lot of popularity in the data science community.

- General purpose programming language
- One of the most beginner-friendly languages because it is close to natural language.
- Industrial strength language for everything from heavy industry to PhD research
- Rapid development cycle, stable libraries, rich ecosystem

## Setup your Python learning environment
1. Create an account on `https://kaggle.com`
2. Go to `https://www.kaggle.com/ryanorsinger/intro-to-python`
3. Click "Copy and Edit" to make your own copy so you can experiment.
4. We will be running Python code inside a "Kernel", which is a special document.

### Using Jupyter Notebooks

- Click into a cell to enter edit mode. You can edit text or edit code.
- `shift + enter` to run a cell of code or click the play icon next to the cell.
- Notebooks have command mode and edit mode
- From edit mode, type the `esc` key to enter command mode.
- Type `h` in command mode to get a list of keyboard shortcuts

### Data types and values

- Booleans (True or False values) denoted by `True` and `False`
- Numbers (integers and floats) `23`, `-5`, `3.141`, `0`
- Strings (text contained inside of 'single' or "double" quotation marks) `"hello"`
- `None` (signifies the absence of value)
- Sequences

    - lists are denoted by square brackets `[1, 2, 3]`. Lists are mutable.

    - tuples `(1, 2, 3, 4, 5)` are immutable lists.

    - sets `{1, 2, 3}` hold only unique values and support set operations

      - union: `{1, 2}.union({2, 3})` is `{1, 2, 3}`
      - intersection:  `{1,2}.intersection({2,3})` is `{2}`, etc...

    - Dictionaries are labeled lists of key => values. `{"vin": "MC3178", "make": "toyota"}`

    - We combine data types to have nested structures. For example, data that you can visualize on a spreadsheet could be a list of lists or a list of dictionaries. 

      ```python
      # What are the data types involved in the following example?
      [{"id": 1, "username":"GraceHopper"}, 
       {"id": 2, "username":"AdaLovelace"}]
      ```

    - Functions: sequences of instructions that operate on inputs to produce outputs.

### Operators and the results of operations 

Operators in programming languages are like math operators like `+`, `-`, `*`, `/`, etc...

In programming, operators return a value with a data type. All values have a data type.

Boolean operators are represented by `and`, `or`, `not`

"Comparisson operators" compare values and return a `True` or `False`.

`==` compares values on each side and returns `True` or `False`. Same with `!=`,`<`, `>`. `<=,` `>=`

Examples: `2 == 2` returns `True`, `2 > 3` is `False`, `3 > 2` is `True`, etc...

### Assignment and reassignment

`x = 2` The single equals symbol is called the `assignment operator`. It assigns variables to point to values. If `x` already points to a value, then `x = 5` reassigns `x`  to be `5`.

### Functions

Functions are reusable blocks of code meant to execute a command or scupt data. Often, we build functions to work like operators where they take in inputs, perform a process, and return the output.

```python
# This block of code is how we would define a function to square a number
def square(input):    
    return input * input
print(square(5))           # prints 5 squared
print(square(square(5)))   # prints the result of squaring the square of five.
```

### Much more practice!


- Goto `https://www.kaggle.com/ryanorsinger/101-exercises`
- Click "Copy and Edit" to make your own copy so you can experiment. 

> "Programming languages allow us to formalize instructions and express logic, business rules, mathematics, processes, and automation instructions in one single language in a way where computers follows those instructions to produce utility for people." - Ryan Orsinger