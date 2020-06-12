# Discovering Disease Outbreaks Starting Repository

Starter repository for Manning PBC: Discovering and Tracking Disease Outbreaks with Data Science and Python

## Setup

This project requires Python 3.7 installed with the [anaconda distribution](https://www.anaconda.com/distribution/).

To install the required libraries in a new virtual environment, run `conda env create -f environment.yml` from the project root 
directory. This will install the  libraries into a virtual env that can be activated with `conda activate discovering-disease-outbreaks`. 

The data is located at `data/headlines.txt`. Run `jupyter notebook` to start a Jupyter Notebook and get coding!

## Tasks

* Extracting city and country name data from text using regular expressions
* Manipulating data and matching location names to geographic coordinates
* Clustering geographic coordinates with KMeans and/or DBSCAN
* Visualizing clusters on a geographic map
* Analyzing algorithm output and tuning model settings to improve results
* Sorting between clusters based on size and within clusters based on distance
* Interpreting algorithm results in the problem domain
* Summarizing findings of a data science project effectively
