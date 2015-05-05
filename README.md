# TutorialMLPython

This is an introductory tutorial of using Python data analysis and machine learning libraries, including Pandas and Scikit-learn for a Kaggle competition problem: Titanic. 
The tutorial was modification of the Pycon UK Introductory Tutorial given by Ezzeri Esa. The original tutorial can be found here:
https://github.com/savarin/pyconuk-introtutorial

In this modified tutorial, more emphasis has been given to: 
- comparison of classifier performance (accuracy and area under the ROC curves) using cross-validation, 
- how to perform data preprocessing and feature selection, and 
- how to tune the hyper-parameters of those classifiers through the use of pipelines. 

## Installation Notes
This tutorial requires *pandas*, *scikit-learn*, and best run  with the IPython Notebook. 
If you're not sure how to install these packages, we recommend the free [Anaconda distribution](http://continuum.io/downloads).

The materials will be best reviewed with the IPython Notebook. You should be able to type
	
	ipython notebook
	
in your terminal window and see the notebook panel load in your web browser.

## Downloading the Tutorial Materials

You can clone the material in this tutorial using git as follows:

	git clone git://github.com/pipalu/TutorialMLPython.git

Alternatively, there is a link above to download the contents of this repository as a zip
file.

## Static Viewing

The notebooks can be viewed in a static fashion using the [nbviewer](http://nbviewer.ipython.org)
site, as per the links in the section below. However, we recommend reviewing them
interactively with the IPython Notebook.

## Presentation Format
The tutorial will start with data manipulation using pandas - loading data, and cleaning data. We then explore the data with some visualisation. 
We'll then use scikit-learn to make predictions. By the end of the tutorial, we would have
worked on the [Kaggle Titanic competition](https://www.kaggle.com/c/titanic-gettingStarted)
from start to finish, through a number of iterations in an increasing order of sophistication.
- [Section 1 - Data cleaning and exploration.ipynb](http://nbviewer.ipython.org/github/pipaLU/TutorialMLPython/blob/master/notebooks/Section%201.%20Data%20cleaning%20and%20exploration.ipynb)
- [Section 2 - Parameter Tuning for Random Forest.ipynb](http://nbviewer.ipython.org/github/pipaLU/TutorialMLPython/blob/master/notebooks/Section%202%20-%20Parameter%20Tuning%20for%20Random%20Forest.ipynb)
- [Section 3 - Cross-validation with ROC analysis.ipynb](http://nbviewer.ipython.org/github/pipaLU/TutorialMLPython/blob/master/notebooks/Section%203.%20Cross-validation%20with%20ROC%20analysis.ipynb)
- [Section 4 - SVM with Feature Selection and Parameter Tuning.ipynb](http://nbviewer.ipython.org/github/pipaLU/TutorialMLPython/blob/master/notebooks/Section%204%20-%20SVM%20with%20Feature%20selection%20and%20Parameter%20Tuning.ipynb)
- [Section 5 - Model Comparison using Pipelines.ipynb](http://nbviewer.ipython.org/github/pipaLU/TutorialMLPython/blob/master/notebooks/Section%205%20-%20Building%20Pipelines%20and%20Model%20Comparison.ipynb)

A [Kaggle account](https://www.kaggle.com/account/register) would be required for the
purposes of making submissions and reviewing our performance on the leaderboard.


## Credits

Most credits go to the original instroctor of the Pycon UK Introductory Tutorial, Ezzeri Esa [savarin] (https://github.com/savarin) for providing the excellent tutorial materials through github.
