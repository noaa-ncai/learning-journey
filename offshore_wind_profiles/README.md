# Training Random Forest Regression model for NOAAOffshoreWindProfiles-USA

This notebook covers the process of training and validating the random forest regression (RFR) model used to generate the NOAA Offshore Wind Profiles - USA dataset. The random forest is a popular and powerful machine learning method that averages predictions over many decision trees to make a final ensemble prediction. The random forest in particular works well for regression and classification problems with nonlinear tabular data. More information on the model can be found online through many resources (simple: https://towardsdatascience.com/random-forest-regression-5f605132d19d/; original publication: https://www.stat.berkeley.edu/~breiman/randomforest2001.pdf). In this notebook, the random forest model is trained using cross validation to tune hyperparameters, tested at independent locations, and applied to new data to generate new wind profiles.

## The Learning Journey Notebook

This learning journey contains a notebook on wind profile prediction:
* [Training Random Forest Regression model for NOAAOffshoreWindProfiles-USA](OffshoreWindProfilesNotebookRevised.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/noaa-ncai/learning-journey/blob/main/offshore_wind_profiles/OffshoreWindProfilesNotebookRevised.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/noaa-ncai/learning-journey/blob/main/offshore_wind_profiles/OffshoreWindProfilesNotebookRevised.ipynb)

## Contributors
- James Frech
- Huai-Min Zhang
