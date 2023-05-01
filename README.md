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


List of suggested topics to cover (not in order right now). We might need to pare the list down.

1. TDA background (ideally (partially) flipped, this will save tremendous time during the workshop, and can be reused in a TDA course, or to teach new students TDA during the course’s off-semesters):
  a. Types of input data:
    i. Time series (real function)
    ii. Images (matrix data)
  b. Introduction to Topology
  c. Complexes
    i. Ripser-Vioteris
    ii. Cubical
  d. Homology
  e. Persistent homology
    i. Stability theory
    ii. Distances between persistence diagrams
  f. The different flavors of persistence
    i. Sublevel persistence
    ii. Point cloud persistence.	
2. Deterministic dynamical systems
    a. Systems with known model: Time series with all states known, focus on available TDA tools for looking at the shape of the attractor (if an attractor is present)
    b. Systems whose model is unknown/complicated: discuss Takens embedding, and then apply TDA to the resulting embedding.
        i. Finding the dimension using classical tools such as FNN
        ii. Finding the delay using classical tools such as autocorrelation function, and the mutual information function
        iii. Discuss more recent tools from our work for finding delay and dimension?
        iv. The only tools we have right now rely on estimating the delay and the dimension separately. There’s a case made in the literature to estimating both simultaneously. Two methods that I’ve been wanting a subset of the students to learn and code (I don’t think they will take more than a week or less) are:
            1. False nearest strands (an improvement to FNN algorithm)
            2. Pecora’s method to simultaneously estimate the delay and the dimension.	
        v. SW1PERS
    c. Graph representations of dynamical systems
    d. Two-state classification of dynamical systems using TDA (chaos versus periodic):
        i. Zigzag persistence
        ii. CROCKER plots
3. Stochastic dynamical systems (at the end, maybe)
    a. Stochastic bifurcations using TDA.

4. Danielle - Talk about how to contribute, opening tickets, more info, etc


## Internal planning:

- Customizing RISE slide style: https://rise.readthedocs.io/en/stable/customize.html#how-to-customize
