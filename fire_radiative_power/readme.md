# Machine Learning for Fire Radiative Power Modeling

Welcome to the machine learning (ML) for Fire Radiative Power (FRP) notebook. In this two-part notebook, we will explore how to train a ML model called a Random Forest (RF) to model FRP one hour into the future. This notebook has several sections and two main parts. In the Environment Part 0, we will import all the necessary environments to run through the notebook.
In Part 1, we will go through a small example to learn how to obtain the input files used to create a machine learning ready (ML-ready) dataset, and how to process the data into a dataset. This is the section that shows the process for developing the dataset, but to keep the notebook simple, this is not the dataset that will be used in part 2 when we learn how to train and test a RF model.\n",
In Part 2, we begin by importing a pre-processed, ML-ready dataset. Then, we will go through the steps on how to train and test a RF model to predict hourly FRP. After, we will demonstrate some package options for analyzing your RF models performance.
If you are interested in using a pre-processed dataset to train RF models, please run through section 0 and then skip forward to section 2.

## Learning Outcomes
       
By the end of this tutorial, you will have:
- learned how to pull RAP data using Herbie
- import RAVE data
- process data into an ML-ready dataset.
        
Additionally, you will have learned how to:
- use that ML-ready dataset in practice to train a RF model
- visualize the performance of that model

## Prerequisites

This is considered a beginner to intermediate notebook for Python-based machine learning. It is helpful to have basic functioning knowledge of the python programming language. This includes using DataFrames. To learn more about any of the tools or more specifics on the machine learning methods in this notebook, please visit the provided references.

## Background
FRP detection of wildland fires is important in calculating a variety of variables, such as smoke emissions, which are necessary for fire weather and air quality simulations. FRP is derived from satellite observations of radiative energy emitted by fires. Modeling FRP into the future has impacts on fire behavior as well as aerosols and smoke modeling. There are challenges to modeling this in real-time, including both missed and false detections as well as errors in retrievals. Satellite scanning angles and resolutions, smoke plumes, and clouds can cause additional challenges. To use satellite data in modeling applications, typically averages over previous FRP instead of continuous FRP are used as inputs. To help provide more continuous FRP forecasts, modeling methods can be applied to previously observed satellite FRP. For this notebook, we look to model hourly FRP from previously observed satellite data combined with numerical weather model inputs.

## Time Estimates
- Estimated text reading time: 15 to 30 min
- Estimated code reading time: 12 to 23 min
- Estimated total reading time: 27 to 53 min

Enjoy!

## Contributors
- Christina Kumler
