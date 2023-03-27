# TITANIC SURVIVAL PREDICTION 

![Titanic prediction](https://miro.medium.com/v2/resize:fit:1200/0*awbekd-RK9TrISOn)

Lets start by importing the different python libraries we will need for the analysis and classification model.

```python
# EDA libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Machine learning libraries
from sklearn.model_selection import cross_val_score
from sklearn.ensemble import RandomForestClassifier, GradientBoostingClasifier
from sklearn.tree import DecisionTreeClassifier
from sklearn.linear_model import LogistiqueRegression
from sklearn.neighbors import KNeighborsClassifier
from sklearn.neural_network import MLPClassifier
```

### Aqcuering the dataset



