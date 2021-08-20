# Boston & San Francisco Airbnb

## Contents

1. [Installation](#installation)
2. [Project Motivation](##project-motivation)
3. [File Descriptions](#file-descriptions)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#Licensing,-Authors,-Acknowledgements)

## Installation

Libraries that are not already installed, can be installed using conda or pip or whatever is suitable for your platform

The libraries used are.

pandas
numpy
matplotlib
seaborn
scikit-learn

[scikit-learn](https://scikit-learn.org/stable/install.html)

[Tensorflow](http://www.tensorflow.org)

[XGBoost](https://xgboost.readthedocs.io/en/latest/index.html)

[TPOT](http://epistasislab.github.io/tpot/)

[Graphviz](https://graphviz.org)
This is a dependency of tensorflow and required for the model summary graphics. See download page of website for install instructions for your platform.

Note dependencies of these packages are also required but should be installed automatically by package managers.

## Project Motivation

1. Look for patterns in prices in different neighbourhoods. Is there a relation between price and neighbourhood.
2. Determine if it is possible to predict a listing price using a model.
3. Select model with best performance, say why it is prefered.

## File Descriptions

Notebooks  - The Jupyter notebooks are listed below

- "1. B & S Airbnb Data Wrangling.ipynb"
- "2. B & S Airbnb - Feature Analysis.ipynb"
- "3. B & S Airbnb Modelling.ipynb"

DataSet
I have included a copy of the dataset in the airbnb folder.
Boston_Listings.csv
SanFrancisco_Listings.csv
In addition to the dataset there are intermediate files exported and loaded by the Python notebooks to manage the data.

## Results

See the second and third notebook for the results of this project.

This project has been written up in the blog post [here](https://medium.com/@hj2048/predictive-modelling-accommodation-listing-prices-a0609dfc1342)

## Licensing, Authors, Acknowledgements

[![Creative Commons Licence](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)

The data file is available on the insideairbnb website  <http://insideairbnb.com/get-the-data.html>

The data is available under a "Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license." <http://creativecommons.org/publicdomain/zero/1.0/>

Acknowledgements : <http://insideairbnb.com/behind.html>
