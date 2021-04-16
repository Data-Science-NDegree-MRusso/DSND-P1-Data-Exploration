# Data-Exploration Project

## Overview

This Project is submitted as part of the Udacity Data Science Nanodegree.

For it the goal is to prepare a Jupyter Notebook to explore a reference data set, in order to use the results as a support for the content of a Medium blog.

## Requirements

In order to facilitate the execution of the Notebook I have prepared an [`environment.yml`](./environment.yml) file to be used to install an environment with [Anaconda](https://www.continuum.io/downloads):

```sh
conda env create -f environment.yml
```

After the installation the environment should be visible via `conda info --envs`:

```sh
# conda environments:
#
dsnd-proj1        /usr/local/anaconda3/envs/dsnd-proj1
...

```

## Notes on the content

The starting data are those provided through the [StackOverflow annual developer survey](https://insights.stackoverflow.com/survey/). 
After browsing a bit through the data, I decided to follow an approach based on the comparison of some classes of categories through the years, rather than an in-depth analysis of a specific years.

The Jupyter notebook in this repo is pretty self-explanatory, but, as a summary, after a first analysis at some indicators characterizing the repondents from a professional perspective (education, job title), and besides looking at some more "traditional" indicators about technology (languages used vs. wanted) I decided to focus on the non-professional aspects of the data, looking at things like the Country where the respondents live, the gender they identify with, and their ethnicity. 

Specifically on gender, a looked at the data and a quick linear model could provide some interesting (I believe) insights on a) the fact that the population of repondents in the past years has been heavily composed by men and 2) that the rate of change at which this situation is evolving is pretty slow.
The Medium post I wrote is available here: as I said there, this analysis has no claim of completeness nor scientific value. However, I think it can provide some objective data point to look into into a situation that many of us have experienced and feel should change.
