# Classification Modeling for Hazardous Rip Current Prediction Learning Journey

This notebook explores binomial (two classes) classification modeling, using an application example of the prediction of hazardous rip currents in San Diego, CA. Rip currents are the leading source of drownings on U.S. beaches, with approaximately 100 fatalies per year. However, it is computationally expensive to predict rip currents using traditional physics-based models that resolve the detailed fluid dynamics that lead to rip current formation. Further, the highly location specific data such as detailed surf zone bathymetry (i.e. the shape of the bottom nearshore) necessary to run these physics-based models is generally not available, making a national implementation of a physics-based approach challenging. Instead, turning the prediction problem into a classification task using machine learning (ML) methods enables incoporating information from physics-based wave and water level models to predict the likelihood of hazardous rip current occurrence. This approach provides actionable guidance to NOAA forecasters at relatively low computational cost and can be run as a national model.

## The Learning Journey Notebook

This learning journey contains notebook on rip current predition:
* [Classification Modeling for Hazardous Rip Current Prediction](Classification_Modeling_for_Hazardous_Rip_Current_Prediction_clean.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/noaa-ncai/learning-journey/blob/main/rip_current/Classification_Modeling_for_Hazardous_Rip_Current_Prediction_clean.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/noaa-ncai/learning-journey/blob/main/rip_current/Classification_Modeling_for_Hazardous_Rip_Current_Prediction_clean.ipynb)

## Contributors
- Andre van der Westhuysen
- Gregory Dusek
- Jung-Sun Im
- Mike Churma
- John F. Kuhn
- Saeideh Banihashemi
