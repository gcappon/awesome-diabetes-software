# Awesome Diabetes Software [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome open-source initiatives frameworks, libraries, software and resources for diabetes research.

- [Awesome Diabetes Software](#awesome-diabetes-software)
- [Diabetes Simulators](#diabetes-simulators)
    - [Type 1 Diabetes Simulators](#t1d-simulators)
    - [Type 2 Diabetes Simulators](#t2d-simulators)
    - [Discrete Events Simulators](#discrete-events-simulators)
- [Analysis Software](#analysis-software)
    - [Software for CGM Data Analysis](#software-for-cgm-data-analysis)
    - [CGM Data Processing Algorithms](#cgm-proessing-algorithms)
- [Algorithms for Diabetes Management](#algorithms-for-diabetes-management)
    - [Glucose Prediction Algorithms](#glucose-prediction-algorithms)
    - [Exercise Management Algorithms](#exercise-management-algorithms)
- [Software for Clinical Trials](#software-for-clinical-trials)
    - [Software to Determine Clinical Trial Outcomes Accuracy](#software-to-determine-clinical-trial-outcomes-accuracy)
    - [Software for Glucose Clamp Experiments](#software-for-glucose-clamp-experiments)
- [Resources](#resources)
    - [Top-level Journals](#top-level-journals)
- [Contributing](#contributing)

---

# Diabetes Simulators 

## Type 1 Diabetes Simulators

* [Simglucose](https://github.com/jxx123/simglucose) - A Type-1 Diabetes simulator implemented in Python for Reinforcement Learning purpose.
* [APS_TestBed](https://github.com/UVA-DSA/APS_TestBed) - A closed-loop testbed for the artificial pancreas system (APS) that evaluates the effectiveness of new control algorithms and other features for the APS in both normal and hazardous environments. The testbed is made up of two APS simulators, UVA/Padova and Glucosym, and a fault injection engine. This repository also includes a dataset we generated with the testbed containing both safe and hazardous data traces from APS.
* [LT1](https://github.com/hpeuscher/loopinsight1) - A closed-loop simulation software of automatic insulin delivery systems for type 1 diabetic persons.
* [CGMSIM](https://lsandini.github.io/cgmsim-site/) - A real-time T1D simulation for teaching/training purposes.
* [TRSET](https://github.com/tidepool-org/data-science-simulator) - A simulation of the Tidepool Loop automatic insulin delivery system for estimating risk of hazardous situations.
* [T1D Exercise Model](https://gitlab.com/csb.ethz/t1d-exercise-model) - A full-day patient simulator including moderate to high intensity exercise.

## Type 2 Diabetes Simulators

* [AAU T2D](https://gitlab.com/aau-adapt-t2d/aau-t2d-simulator) - A type 2 diabetes simulator with web based GUI.
## Discrete Events Simulators

* [CarbMetSim](https://github.com/mukulgoyalmke/CarbMetSim) - A discrete event simulator for tracking blood glucose level based on carbodydrate metabolism in human body.

## Digital Twin-Based Simulators

* [ReplayBG](https://github.com/gcappon/replay-bg) - ReplayBG is a digital twin-based MATLAB® toolbox to assess new strategies for type 1 diabetes management on retrospective patient data.
* [PyReplayBG](https://github.com/gcappon/py_replay_bg) - The Python porting of [ReplayBG](#replaybg).
  
# Analysis Software

## Software for CGM Data Analysis

* [AGATA](https://github.com/gcappon/agata) - AGATA (Automated Glucose dATa Analysis) is a MATLAB® toolbox to analyse glucose data.
* [AGATA](https://github.com/gcappon/py_agata) - The Python porting of [AGATA](#agata)
* [rGV](https://cran.r-project.org/web/packages/rGV/index.html) - Reads in continuous glucose monitor data of many different formats, calculates a host of glycemic variability metrics, and plots glucose over time.
* [CGMTSA](https://github.com/RyanJ-Shao/CGMTSA) - <No description given>
* [CGDA](https://github.com/EvdVossen/CGDA) - CGDA package to process Continuous Glucose Measurements data.
* [iglu](https://github.com/irinagain/iglu) - Interpreting data from Continuous Glucose Monitors (CGMs).
* [cgmquantify](https://github.com/brinnaebent/cgmquantify) - Python package for analyzing glucose and glucose variability.
* [GLU](https://github.com/MRCIEU/GLU) - A tool for analysing continuously measured glucose in epidemiology.
* [cgmanalysis](https://cran.r-project.org/web/packages/cgmanalysis/index.html) - R package with several different functions for cleaning and analyzing continuous glucose monitor data.
* [CGManalyzer](https://cran.r-project.org/web/packages/CGManalyzer/index.html) - R package with functions necessary for the complete analysis of a continuous glucose monitoring study.
* [Tidepool Platform](https://github.com/tidepool-org/blip) - Diabetes device data standardization and visualization, providing consistent reporting for patients and providers.
* [GVAP](https://sourceforge.net/projects/glyvariab/files/?source=navbar) - <No description given>
* [EasyGV](www.phc.ox.ac.uk/research/technology-outputs/easygv) - Software that allows you to calculate 10 different measures of glycaemic variability (GV) from continuos glucose monitoring data using a simple interface.

## CGM Data Processing Algorithms

* [Bayesian-Denoising-CGM](https://github.com/NunzioCamer/Bayesian-Denoising-CGM) - A Bayesian denoising algorithm to deal with colored, non-stationary noise in continuous glucose monitoring timeseries.

# Algorithms for Diabetes Management

## Glucose Prediction Algorithms

* [PhyPredict](https://github.com/checoisback/phy-predict) - Algorithm to predict glucose ahead in time by using a non-linear physiological model of glucose-insulin dynamics and the particle filter.
* [GluPredKit](https://github.com/miriamkw/GluPredKit) - Software to steamline data-driven blood glucose prediction,  including data fetching, processing, training, evaluation and real-time predictions.

## Exercise Management Algorithms

* [T1D Exercise Adjustment](https://gitlab.com/csb.ethz/t1d-exercise-adjustment) - Exercise and T1D: Modeling, simulation and evaluation of treatment strategies.
* [T1D Exercise Control](https://gitlab.com/csb.ethz/t1d-exercise-control) - Exercise and T1D: using insulin sensitivity estimation with model predictive control.

# Software for Clinical Trials

## Software to Determine Clinical Trial Outcomes Accuracy

* [AnalyticalTBRestimation](https://github.com/NunzioCamer/AnalyticalTBRestimation) - Analytical computation of Time Below Range estimation error based on the number of Continuous Glucose Monitoring samples.

## Software for Glucose Clamp Experiments

* [Gluclas](https://github.com/jp993/gluclas) - Gluclas (GLUcose CLamp ASsistant) is a free software for suggesting glucose infusion rate adjustments during manual glucose clamp experiments.

# Resources

Where to discover learning resources.

## Top-level Journals

* Bioengineering
    * [IEEE Transaction on Biomedical Engineering](https://www.embs.org/tbme/) - IEEE Transactions on Biomedical Engineering contains basic and applied papers dealing with biomedical engineering. Papers range from engineering development in methods and techniques with biomedical applications to experimental and clinical investigations with engineering contributions.
    * [Journal of Diabetes Science and Technology](https://journals.sagepub.com/home/dst) - Journal of Diabetes Science and Technology (JDST) is a bi-monthly, peer-reviewed scientific journal published by Diabetes Technology Society (DTS). JDST covers scientific and clinical aspects of diabetes technology, the development and use of mobile applications and wireless communication, as well as bioengineered tools.

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/gcappon/awesome-diabetes-simulation/blob/master/CONTRIBUTING.md) first.

- - -

If you have any question about this opinionated list, do not hesitate to contact me via email giacomo.cappon@unipd.it or open an issue on GitHub.
