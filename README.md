## Hello! Here you can find examples on how to build basic machine learning models

You can use this code as a base for starting your own machine learning projects!

### Introduction

Python is a easy to learn programming language that is perfect for starters. If you come from a academic background and have use Matlab before the python sintax will look very familiar to you. On the other hand, if its your first time programming in any language there are some little things that will easy your learning curve and I'm going to do my best effort to summary them in this webpage.

### Python have libraries. What are them?

TLDR: A library is useful code some cool genius programmers to help other people do common (or not so common) tasks in a easy way.

The classical libraries used in machine learning projects are:

Pandas for data handling (wrangling and cleaning)
Numpy or Scipy for scientific computing (math like linear algebra, optimization and other important operations)
Scikit-learn (sklearn) for ready to train machine learning models
Matplotlib for plotting your data or results

#### And how do i can use them?

you just have to "import" them as follows.

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

This common libraries have standard aliases that you could use in your code to reduce it while other people would still be able to understand which libbraries you are using.

But what about sklearn? The models in this library are accesible by importing them as classes to do this you use the from statement as seen here.



```python
from sklearn.linear_model import LogisticRegression
from sklearn.neighbors import KNeighborsClassifier
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
```


### The rest is your work!! go checkout the [code example](https://github.com/Claudio9701/classification_models_example/blob/master/classification_models.ipynb).

Contributions are well received, you could comment the code better or maybe maje some useful functions for machine learning.
Don't hesitate to use the [Issues section](https://github.com/Claudio9701/classification_models_example/issues) if you have doubts or complications.
