# Tropical Cyclone PRecipitation, Infrared, Microwave, and Environmental Dataset Learning Journey

The Tropical Cyclone Precipitation, Infrared, Microwave, and Environmental Dataset (TC PRIMED) Learning Journey provides users with interactive documentation for the dataset as well as examples of artificial intelligence (AI) and machine learning applications.

## TC PRIMED

TC PRIMED aims to ameliorate the issue of disparate data sources by consolidating forecast products from various data sources into a single repository. Centered around satellite passive microwave observations of tropical cyclones, TC PRIMED contains over 197,000 overpasses of 2,300 global tropical cyclones from 1998 to 2021. The dataset includes
* NOAA National Weather Service National Hurricane Center and Central Pacific Hurricane Center and Department of Defense Joint Typhoon Warning Center global tropical cyclone characteristics from the best-track database
* Multi-agency inter-calibrated, multi-channel microwave brightness temperatures
* Goddard Profiling Algorithm (GPROF) retrieved rainfall
* Geostationary satellite infrared imagery
* ECMWF fifth-generation reanalysis (ERA5) product fields and derived environmental diagnostics
* TRMM/GPM precipitation radar variables
* More detail about TC PRIMED is available on the [project page](https://rammb-data.cira.colostate.edu/tcprimed/) and two publications [^1] [^2].

## Learning Journey concept

A Learning Journey is a series of modules that use interactive notebook open-science technology (e.g., Jupyter notebooks). The Learning Journey concept originated with the [NOAA Center for Artificial Intelligence](https://www.noaa.gov/noaa-center-for-artificial-intelligence/noaa-center-for-artificial-intelligence) as a means by which to allow the NOAA workforce and public to interact with AI-ready datasets and AI applications. In a Learning Journey, the user can choose an appropriate path based on their familiarity with AI techniques or specific data.

## TC PRIMED Learning Journey
This set of learning journey notebooks is divided into the following chapters:
* [Chapter 0: What is TC PRIMED?](TCPRIMED_Chap0_Introduction.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap0_Introduction.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap0_Introduction.ipynb)

* [Chapter 1a: NetCDF Files](TCPRIMED_Chap1a_NetCDF.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap1a_NetCDF.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap1a_NetCDF.ipynb)

* [Chapter 1b: The Overpass File](TCPRIMED_Chap1b_OverpassFile.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap1b_OverpassFile.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap1b_OverpassFile.ipynb)

* [Chapter 1c: The Environmental File](TCPRIMED_Chap1c_EnvironmentalFile.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap1c_EnvironmentalFile.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap1c_EnvironmentalFile.ipynb)

* [Chapter 2: Composite Analysis](TCPRIMED_Chap2_CompositeAnalysis.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap2_CompositeAnalysis.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap2_CompositeAnalysis.ipynb)

* [Chapter 3: Pixel-based Artificial Neural Network Application](TCPRIMED_Chap3_Pixel-BasedNeuralNetwork.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap3_Pixel-BasedNeuralNetwork.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap3_Pixel-BasedNeuralNetwork.ipynb)

* [Chapter 4: Regridding Satellite Swath Data](TCPRIMED_Chap4_RegriddingSwathData.ipynb)<br>
  [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap4_RegriddingSwathData.ipynb)<br>
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CSU-CIRA/tcprimed_learning_journey/blob/main/TCPRIMED_Chap4_RegriddingSwathData.ipynb)

Launch all notebooks in the Learning Journey using Jupyter lab via Binder via the badge below.<br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CSU-CIRA/tcprimed_binder_sandbox/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252FCSU-CIRA%252Ftcprimed_learning_journey%26urlpath%3Dlab%252Ftree%252Ftcprimed_learning_journey%252F%26branch%3Dmain)


> **Warning:**
> If you go through the learning journey material using Binder or Google Colab, your
> changes will not be saved unless you download the notebooks before exiting
> your browser tab.

## Contributors

* [Naufal Razin, CSU/CIRA](https://www.cira.colostate.edu/staff/razin-naufal/)
* [Kathy Haynes, CSU/CIRA](https://www.cira.colostate.edu/staff/haynes-katherine/)
* [Chris Slocum, NOAA/STAR](https://www.star.nesdis.noaa.gov/star/Slocum_C.php)

## References
[^1]: Razin, M. N., C. J. Slocum, J. A. Knaff, P. J. Brown, and M. M. Bell, 2022: Tropical Cyclone Precipitation, Infrared, Microwave, and Environmental Dataset (TC PRIMED). Bull. Amer. Met. Soc., Early Online Release. [https://doi.org/10.1175/BAMS-D-21-0052.1](https://doi.org/10.1175/BAMS-D-21-0052.1).
[^2]: Slocum, C. J., M. N. Razin, J. A. Knaff, and S. P. Stow, 2022: Does ERA5 mark a new era for resolving the tropical cyclone environment? J. Climate., 35, 3547–3564, [https://doi.org/10.1175/JCLI-D-22-0127.1](https://doi.org/10.1175/JCLI-D-22-0127.1).
