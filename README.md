# Machine-Learning-Primer
Machine Learning collects from projects I made before :)
check the presentation, but basically -I said it BASIC- is about the exercise of using this model to predict the value of the stock based on the dataset by train the model, just because I can, and I want to get crazy with all that buzzword of ML as a minor.

# Sampling and comparison
![screenshot](https://github.com/elnemesisdivina/Machine-Learning-Primer/blob/master/comparison%20stock%20prediction.jpg)

## So as the receipe:

### Get your fnacy jupyter notebooks docker image from docker hub

```bash
docker pull jupyter/scipy-notebook
```

### Then run it from CLI and just make sure you place the jupiter nobook and your dataset on mapping path to volume for container, also port can be used so chek it.

```bash
docker run --rm -it -p 8888:8888 -v ~/notebooks:/home/vray  jupyter/scipy-notebook
```

### it containes all necesary libraies to be invoke from notebook just make shure is upp an running before import them on notebook, this by login in this local web page http://127.0.0.1:8888 jsut check for auto token generated for login something like this token=f4ac9013f3c4be8bfc9b5e5681df1fd60bb39bb55de4395c


```python
import sklearn
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

### enjoy understanding how simple can be the use of mx+b, python, scikit learn librady and dcoker container for this, and sorry for the typos :)

