#  Topological Signal Processing for Dynamical Systems

This repository contains the content for a [minitutorial](https://www.siam.org/conferences/cm/program/minitutorials/ds23-minitutorials) for the [2023 SIAM Conference on Applications of Dynamical Systems (DS23)](https://www.siam.org/conferences/cm/conference/ds23). 

- [Part I Information](https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=75586)
- [Part II Information](https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=77160)

Contributors to this minitutorial are:

- [Firas Khasawneh](firaskhasawneh.com)
- [Elizabeth Munch](elizabethmunch.com)
- [Max Chumley](https://www.linkedin.com/in/max-chumley)
- [Danielle Barnes](https://github.com/barnesd8) 

## Abstract

Persistent homology, the flagship method of topological data analysis (TDA), can be used to provide a quantitative summary of the shape of data.  There is now extensive work using the following pipeline. Start with a realization of a dynamical system, perhaps after reconstruction from time series data. Treat this data as a discrete metric space, and construct a filtration of a simplicial complex that encodes information about the shape.  Then, use persistent homology to determine when structures appear and disappear in this filtration, which can in turn be used as input to tools such as machine learning models. 

This mini-tutorial will cover the basics of each piece of the aforementioned pipeline, as well as show more recently studied modifications that show a great deal of promise for future analysis of dynamical systems with TDA. This tutorial will be run using active learning, with participants coding examples in python in provided Jupyter notebooks, making extensive use of the open-source package [teaspoon](https://github.com/TeaspoonTDA/teaspoon). 

## Schedule 


### Session 1: Persistent Homology Basics

1. Introduction, Simplicial complexes & Homology (Liz starts slides, 20 minutes)
   - Jupyter notebook (20 min)
2. Persistent homology (10 min)
   - Jupyter notebook (20 min)
3. Flavors of persistence: Rips & Images (20 min)
   - Jupyter notebook (2o min, Sunia creating)
4. Distances on persistence diagrams & Vectorization (10 min)
   
### Session 2: Using Persistence for Signal Processing

1. Embedding of Time series (20 min)
   - Jupyter notebook, focus on persistence examples (20 min)
   - Shows different behaviors like chaotic/periodic with persistence outputs
2. Graph representations of time series (20 min)
   - Jupyter notebook (20 min, Max has started)
3. Crocker plots (10 min)
   - Jupyter notebook (10 min)
4. Stochastics (10 min, Sunia)
5. Teaspoon contribution (10 min; Danielle)



## Internal planning:

- Customizing RISE slide style: https://rise.readthedocs.io/en/stable/customize.html#how-to-customize
