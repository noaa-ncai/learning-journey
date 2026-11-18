# Tropical Cyclone Rapid Intensification Model Learning Journey

Tropical cyclone rapid intensification is a challenge for emergency preparedness given the rarity of the event and challenges in predicting it. To better predict tropical cyclone rapid intensification, forecasters rely on traditional and contemporary machine learning statistical models. These models use data from numerical weather prediction models and satellite observations to characterize the respective environmental state around the tropical cyclone and the tropical cyclone convective structure.

In this learning journey, you will
* learn to extract and pre-process environmental and satellite information of tropical cyclones along with the corresponding future 24-hour intensity change; and
* use several different machine learning statistical models to compare and contrast their strengths and weaknesses.

The models developed in this Learning Journey series are highly simplified versions of those commonly used by tropical cyclone forecasters at the NOAA NWS National Hurricane Center and Central Pacific Hurricane Center, and the U.S. Department of Defense's Joint Typhoon Warning Center. This work uses Tropical Cyclone Precipitation, Infrared, Microwave, and Environmental Dataset (TC PRIMED)[^1] [^2] and builds off of the TC PRIMED learning journey, which is available in the [learning journey library](https://github.com/noaa-ncai/learning-journey/tree/main/tcprimed).

## TC PRIMED Learning Journey
This set of learning journey notebooks is divided into the following chapters:
* [Chapter 1: Data Collection and Preprocessing](RI_Chapter1_DataPreprocessing.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/noaa-ncai/learning-journey/blob/main/rapid_intensification/RI_Chapter1_DataPreprocessing.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/noaa-ncai/learning-journey/blob/main/rapid_intensification/RI_Chapter1_DataPreprocessing.ipynb)

* [Chapter 2: ML-Based RI Model](RI_Chapter2_ML.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/noaa-ncai/learning-journey/blob/main/rapid_intensification/RI_Chapter2_ML.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/noaa-ncai/learning-journey/blob/main/rapid_intensification/RI_Chapter2_ML.ipynb)


## Contributors

* [Naufal Razin, CSU/CIRA](https://www.cira.colostate.edu/staff/razin-naufal/)
* [Marie McGraw, CSU/CIRA](https://marie-mcgraw.github.io/)
* [Chris Slocum, NOAA/STAR](https://www.star.nesdis.noaa.gov/star/Slocum_C.php)

## References
[^1]: Razin, M. N., C. J. Slocum, J. A. Knaff, P. J. Brown, and M. M. Bell, 2023: Tropical Cyclone Precipitation, Infrared, Microwave, and Environmental Dataset (TC PRIMED). Bull. Amer. Met. Soc., 104, E1980–E1998, [https://doi.org/10.1175/BAMS-D-21-0052.1](https://doi.org/10.1175/BAMS-D-21-0052.1).
[^2]: Slocum, C. J., M. N. Razin, J. A. Knaff, and S. P. Stow, 2022: Does ERA5 mark a new era for resolving the tropical cyclone environment? J. Climate., 35, 3547–3564, [https://doi.org/10.1175/JCLI-D-22-0127.1](https://doi.org/10.1175/JCLI-D-22-0127.1).
