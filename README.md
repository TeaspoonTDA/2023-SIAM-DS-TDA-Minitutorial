#  Topological Signal Processing for Dynamical Systems

This repository contains the content for a [minitutorial](https://www.siam.org/conferences/cm/program/minitutorials/ds23-minitutorials) for the [2023 SIAM Conference on Applications of Dynamical Systems (DS23)](https://www.siam.org/conferences/cm/conference/ds23). 

- [Part I Information](https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=75586): 1:20-3:20PM 
- [Part II Information](https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=77160): 4:45-6:45PM
- Both sessions in Lloyd Center Ballroom - 1st Level

Contributors to this minitutorial are:

- [Firas Khasawneh](firaskhasawneh.com)
- [Elizabeth Munch](elizabethmunch.com)
- [Max Chumley](https://www.maxchumley.com)
- [Danielle Barnes](https://github.com/barnesd8) 
- [Sunia Tanweer](stanweer1.github.io)

## Abstract

Persistent homology, the flagship method of topological data analysis (TDA), can be used to provide a quantitative summary of the shape of data.  There is now extensive work using the following pipeline. Start with a realization of a dynamical system, perhaps after reconstruction from time series data. Treat this data as a discrete metric space, and construct a filtration of a simplicial complex that encodes information about the shape.  Then, use persistent homology to determine when structures appear and disappear in this filtration, which can in turn be used as input to tools such as machine learning models. 

This mini-tutorial will cover the basics of each piece of the aforementioned pipeline, as well as show more recently studied modifications that show a great deal of promise for future analysis of dynamical systems with TDA. This tutorial will be run using active learning, with participants coding examples in python in provided Jupyter notebooks, making extensive use of the open-source package [teaspoon](https://github.com/TeaspoonTDA/teaspoon). 

## Schedule 


### Session 1: Persistent Homology Basics

0. Welcome Remarks and Introduction (5 minutes)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-0-Welcome.ipynb)
   - Presenter: Firas Khasawneh & Liz Munch
1. Simplicial complexes & Homology (30 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-1-SimplicialCpx_Homology.ipynb)
   - [Jupyter notebook](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-1-Wkst-Intro_SimplicialCpx_Homology.ipynb) 
   - Presenter: Liz Munch
2. Persistent homology (30 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-2-PersistentHomology.ipynb) 
   - [Jupyter notebook](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-2-Wkst-PersistentHomology.ipynb) 
   - Presenter: Liz Munch
3. Persistence Pipelines: Rips & Images (30 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-3-PersistencePipelines.ipynb)
   - [Jupyter notebook](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-3-PersistencePipelines.ipynb) 
   - Presenter: Firas Khasawneh 
4. Distances on persistence diagrams & Vectorization (10 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/1-4-DistancesAndVectorization.ipynb)
   - Presenter: Danielle Barnes
5. Session 1 Wrap up (5 minutes)
   - Slides
   - Presenter: Firas Khasawneh & Liz Munch
   
### Session 2: Using Persistence for Signal Processing

0. Welcome Remarks and Introduction (5 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-0-Welcome.ipynb)
   - Presenter: Firas Khasawneh & Liz Munch
1. Embedding of Time series (40 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-1-Embedding.ipynb)
   - [Jupyter notebook](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-1-Wkst-Embedding.ipynb)
   - Presenter: Max Chumley
2. Graph representations of time series (30 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-2-GraphTimeSeries.ipynb)
   - Jupyter notebook 
   - Presenter: Max Chumley
3. Crocker plots (20 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-3-CrockerPlots.ipynb) 
   - Jupyter notebook 
   - Presenter: Sunia Tanweer
4. Stochastics (10 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-4-Stochastics.ipynb)
   - Presenter: Sunia Tanweer
5. Teaspoon contribution (5 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-5-ContributionAndConclusion.ipynb) 
   - Presenter: Danielle Barnes
6. Session 2 Wrap up (5 min)
   - [Slides](https://github.com/TeaspoonTDA/2023-SIAM-DS-TDA-Minitutorial/blob/main/2-6-Wrapup.ipynb)
   - Presenter: Firas Khasawneh & Liz Munch

### Installing Teaspoon

Since this minitutorial is based on various computational methods and software packages, you can either install the required packages locally, or use the provided jupyter servers to participate in the workshop.  If you choose to install locally, we ask that you do so before the tutorial.  We will be able to provide limited troubleshooting for installs, so if you are encountering issues we recommend you use the provided jupyter servers.  If you are using the servers, you will also need a GitHub account to authenticate.

#### Create a GitHub Account

Please follow the [GitHub signup instructions](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account).

#### Server Login Information

To run your computations on a provided Jupyter Server, choose initially login choosing one of the URL's below as instructed:

[Server 1](https://github.com/TeaspoonTDA/teaspoon)
[Server 2](https://github.com/TeaspoonTDA/teaspoon)
[Server 3](https://github.com/TeaspoonTDA/teaspoon)

Note:  These links will not work until the minitutorial begins and currently redirect the teaspoon repository.

#### Local Install

To install [teaspoon](https://github.com/TeaspoonTDA/teaspoon) locally, please follow the directions provided in [Getting Started](https://teaspoontda.github.io/teaspoon/installation.html#).  There are two system dependencies, [cmake](https://cmake.org/install/) and [boost for unix](https://www.boost.org/doc/libs/1_66_0/more/getting_started/unix-variants.html) or [boost for windows](https://www.boost.org/doc/libs/1_62_0/more/getting_started/windows.html), that are required.  While we make every effort to ensure compatibility across operating systems, we cannot guarantee you will not encounter install issues.

In addition to teaspoon, RISE and giotto-tda are required for use of the slide decks and specific portions of the minitutorial.  Once system dependencies are installed, to install the required python packages you should be able to run:

``` 
pip install teaspoon
pip install RISE
pip install giotto-tda
```
