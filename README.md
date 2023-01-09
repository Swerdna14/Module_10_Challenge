# K-Means Crypto Clustering
**Module 10 Challenge**

This challenge required us to use the K-Means clustering and the elbow curve to create a clustering and analyse the trends of crypto investment data.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [Pandas](https://github.com/google/pandas) - Pandas is a powerfull tool for data analysis and manipulation. Pandas provides a plethora of useful functions that make it easy to express, analyze, and manipulate data.

* [Hvplot](https://github.com/google/hvplot) - This Module provides a high-level potting API that allows for users to easily generate a wide array of plot types. HvPlot's main benefit is that it allows for very interactive visualizations.

* [scikit-learn](https://scikit-learn.org/stable/) - This is a machine learning library for the python programming language. This library allows for the use of multiple machine learning models, tools, and algorithms.

---

## Installation Guide

In order to use this program please import and utilize the following libraries and dependencies: 

```python
import pandas as pd
import hvplot.pandas
from pathlib import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA, KernelPCA
from sklearn.preprocessing import StandardScaler
```

---  

### **Run instructions:**
To run this analysis, simply clone the repository or download the files. Open a terminal instance and start a jupyter lab instance by using the following command:
```python
jupyter lab
```
Once it has opened, navigate to the file named **crypto_investments.ipynb**.

---

## Results

In this challenge, crypto market data gets scaled so it is standardised across all of the different crypto coins to make it a fair comparison.

From there, the data is then used to find the best value for the K-Means cluster number by using the Elbow Curve method.
Once it was found, the data was then plotted on a scatterplot to see it visually in its clusters.

To compare it, the PCA method was applied to the original scaled data and the same process of finding the optimal number of clusters through the ELbow Curve method was used.
The PCA dataframe was then plotted on a scatterplot.

The originally scaled data was compared to the PCA data, both the Elbow Curves and Scatterplots were analysed and some questions were answered.

---

## Contributors

This project was created as part of the module 14 challenge in the Monash University Fintech Bootcamp 2022 Program by:

Lachlan Andrews

Email: swerdna14@gmail.com

LinkedIn: lachlanjandrews
