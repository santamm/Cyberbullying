# Cyberbullying
Cyberbullying detection using Emolex lexicon to analyse tweets.
This template will be used for an hackaton organized by [AIInAfrica}(https://aiinafrica.org)


### Table of Contents

1. [Installation](#installation)
2. [Project Analysis](#motivation)
3. [Metric](#metric)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
The code in this project is written in Python 3.6.6 :: Anaconda custom (64-bit).
The following additional libraries have been used:
* pandas
* numpy
* matplotlib
* seaborn
* sklearn
* warnings
* time
* mpl_toolkits.mplot3d



## Project Analysis<a name="motivation"></a>
We present an analysis of emotions linked to tweets in order to detect instances of cyberbulling.
The tweets dataset has been manually collected using twitter APIs by Margarita Bugueño, Fabián Fernandez and Francisco Mena.

The NRC Emotion Lexicon (aka Emolex) is a list of English words and their associations with eight basic emotions (anger, fear, anticipation, trust, surprise, sadness, joy, and disgust) and two sentiments (negative and positive). It has been developed by [Saif Mohammad](https://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm) and is a lexic tag based on the Plutchick wheel of emotions. The annotations were manually done by crowdsourcing.


## Metric<a name="metric"></a>
 The metric used to compare all models is RMSE. The loss function used is MSE.

## File Descriptions <a name="files"></a>
The Jupyter notebooks included in this project are:
- Cyberbullying.ipynb


Data files (under data directory):
- tweets : directory with repository of csv files 


## Results<a name="results"></a>
We load a dataset of tweets and score them using Emolex. The aggregated data ais then displayed using Visualizations.
We want to try find a metric to detect potential "bullies" "or bullied" twitter users.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>
For licensing see LICENSE file.
The tweets dataset has been manually collected using twitter APIs by Margarita Bugueño, Fabián Fernandez and Francisco Mena.
Emolex has been developed by [Saif Mohammad](https://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm)
