# Analysis On Quality of White Wine

## Project: Investigate Factors That Affect Quality of White Wine

Exploratory Data Analysis Project

### Install

This project requires Python 3 and the following Python libraries installed:

* <a href="http://pandas.pydata.org/">Pandas</a>
* <a href="https://matplotlib.org/">matplotlib</a>

You will also need to have software installed to run and execute an <a href="http://ipython.org/notebook.html">iPython Notebook</a>

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select the Python 3 installer and not the Python 2.x installer.

### Code

* `Analysis on White Wine Quality.ipynb`: This is the main file where you will be performing your work on the project

* `wineQualityWhites.csv`: The project dataset. You will load this data in the notebook.

### Run

In a terminal or command window, navigate to the top-level project directory `Analysis-On-Quality-of-White-Wine-/` (that contains this README) 
and run one of the following commands:

```
ipython notebook Analysis on White Wine Quality.ipynb
```
or

```
jupyter notebook Analysis on White Wine Quality.ipynb
```
This will open the Jupyter Notebook software and project file in your browser.

### Data

The White Wine Quality dataset consists of 4898 observations and 12 attributes out of which 11 attributes quantify the chemical properties of wine.

### Sources

Created by: Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) @ 2009

### Past Usage:

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. 
Modeling wine preferences by data mining from physicochemical properties.
In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

The inputs include objective tests (e.g. PH values) and the output is based on sensory data
(median of at least 3 evaluations made by wine experts). 
Each expert graded the wine quality between 0 (very bad) and 10 (very excellent). 
Several data mining methods were applied to modelthese datasets under a regression approach. 
The support vector machine model achieved thebest results. 
Several metrics were computed: MAD, confusion matrix for a fixed error tolerance (T),
etc. Also, we plot the relative importances of the input variables (as measured by a sensitivity
analysis procedure).

### Relevant Information:

The dataset is related to white variants of the Portuguese "Vinho Verde" wine.

For more details, consult: http://www.vinhoverde.pt/en/ or the reference [Cortez et al., 2009].

Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables 
are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

#### Attribute Information:

For more information, read [Cortez et al., 2009].

Input variables (based on physicochemical tests):

   * `fixed acidity` (tartaric acid - g / dm^3)
   
   * `volatile acidity` (acetic acid - g / dm^3)
   
   * `citric acid` (g / dm^3)
   
   * `residual sugar` (g / dm^3)
   
   * `chlorides` (sodium chloride - g / dm^3
   
   * `free sulfur dioxide` (mg / dm^3)
   
   * `total sulfur dioxide` (mg / dm^3)
   
   * `density` (g / cm^3)
   
   * `pH`
   
   * `sulphates` (potassium sulphate - g / dm3)
   
   * `alcohol` (% by volume)

Output variable (based on sensory data): 

   * `quality` (score between 0 and 10)

#### Missing Attribute Values: 
None

#### Attributes Description:

Input variables (based on physicochemical tests):

   * `fixed acidity`: Most acids involved with wine or fixed or nonvolatile (do not evaporate readily).
   
   * `volatile acidity`: The amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste.
   
   * `citric acid`: Found in small quantities, citric acid can add 'freshness' and flavor to wines.
   
   * `residual sugar`: The amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet.
   
   * `chlorides`: The amount of salt in the wine.
   
   * `free sulfur dioxide`: The free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine.
   
   * `total sulfur dioxide`: Amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine.
   
   * `density`: The density of water is close to that of water depending on the percent alcohol and sugar content.
   
   * `pH`: Describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale.
   
   * `sulphates`: A wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant.
   
   * `alcohol`: The percent alcohol content of the wine.

Output variable (based on sensory data): 

   * `quality`: The score between 0 and 10.
