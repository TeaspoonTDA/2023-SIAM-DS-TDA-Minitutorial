#  Topological Signal Processing for Dynamical Systems

This repository contains the content for a [minitutorial](https://www.siam.org/conferences/cm/program/minitutorials/ds23-minitutorials) for the [2023 SIAM Conference on Applications of Dynamical Systems (DS23)](https://www.siam.org/conferences/cm/conference/ds23). 

- [Part I Information](https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=75586): 1:20-3:20PM 
- [Part II Information](https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=77160): 4:45-6:45PM
- Both sessions in Lloyd Center Ballroom - 1st Level

Contributors to this minitutorial are:

- [Firas Khasawneh](firaskhasawneh.com)
- [Elizabeth Munch](elizabethmunch.com)
- [Max Chumley](maxchumley.com)
- [Danielle Barnes](https://github.com/barnesd8) 
- [Sunia Tanweer](stanweer1.github.io)

## Abstract

Persistent homology, the flagship method of topological data analysis (TDA), can be used to provide a quantitative summary of the shape of data.  There is now extensive work using the following pipeline. Start with a realization of a dynamical system, perhaps after reconstruction from time series data. Treat this data as a discrete metric space, and construct a filtration of a simplicial complex that encodes information about the shape.  Then, use persistent homology to determine when structures appear and disappear in this filtration, which can in turn be used as input to tools such as machine learning models. 

This mini-tutorial will cover the basics of each piece of the aforementioned pipeline, as well as show more recently studied modifications that show a great deal of promise for future analysis of dynamical systems with TDA. This tutorial will be run using active learning, with participants coding examples in python in provided Jupyter notebooks, making extensive use of the open-source package [teaspoon](https://github.com/TeaspoonTDA/teaspoon). 

## Schedule 


### Session 1: Persistent Homology Basics

0. Welcome Remarks and Introduction
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-0-Welcome.ipynb)
   - Presenter: Firas Khasawneh & Liz Munch
1. Simplicial complexes & Homology (20 minutes)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-1-SimplicialCpx_Homology.ipynb)
   - [Jupyter notebook](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-1-Wkst-Intro_SimplicialCpx_Homology.ipynb) (20 min)
   - Presenter: Liz Munch
2. Persistent homology (10 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-2-PersistentHomology.ipynb) 
   - [Jupyter notebook](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-2-Wkst-PersistentHomology.ipynb) (20 min)
   - Presenter: Liz Munch
3. Persistence Pipelines: Rips & Images (20 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-3-PersistencePipelines.ipynb)
   - [Jupyter notebook](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-3-PersistencePipelines.ipynb) (20 min)
   - Presenter: Firas Khasawneh 
4. Distances on persistence diagrams & Vectorization (10 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-4-DistancesAndVectorization.ipynb)
   - Presenter: Danielle Barnes
5. Session 1 Wrap up
   - Slides
   - Presenter: Firas Khasawneh & Liz Munch
   
### Session 2: Using Persistence for Signal Processing

0. Welcome Remarks and Introduction
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-0-Welcome.ipynb)
   - Presenter: Firas Khasawneh & Liz Munch
1. Embedding of Time series (20 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-1-Embedding.ipynb)
   - Jupyter notebook (20 min)
   - Presenter: Max Chumley
2. Graph representations of time series (20 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-2-GraphTimeSeries.ipynb)
   - Jupyter notebook (20 min)
   - Presenter: Max Chumley
3. Crocker plots (10 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-3-CrockerPlots.ipynb) 
   - Jupyter notebook (10 min)
   - Presenter: Sunia Tanweer
4. Stochastics (10 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-4-Stochastics.ipynb)
   - Presenter: Sunia Tanweer
5. Teaspoon contribution (10 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-5-ContributionAndConclusion.ipynb) 
   - Presenter: Danielle Barnes
6. Session 2 Wrap up
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-6-Wrapup.ipynb)
   - Presenter: Firas Khasawneh & Liz Munch
