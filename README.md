# Repo of my Jupyter Notebooks

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/aschleg/IPython_Notebooks/master)

This repository is more or less a central location of my [jupyter notebooks](http://jupyter.org/) on various topics in hopes of keeping more organized. Some of these notebooks may appear in other projects where appropriate. Interactive versions of the notebooks can be launched through [Binder](https://mybinder.org/) by clicking the `launch binder` badge at the top of the `README.md`.

## Contents

* finance
	- Collection of notebooks of some computational financial functions.
		* [Black-Scholes Formula](https://github.com/aschleg/IPython_Notebooks/blob/master/finance/Black-Scholes%20Formula.ipynb)
		* [Implied Volatility](https://github.com/aschleg/IPython_Notebooks/blob/master/finance/Implied%20Volatility.ipynb)
		* [Put-Call Parity of Vanilla European Options](https://github.com/aschleg/IPython_Notebooks/blob/master/finance/Put-Call%20Parity%20of%20Vanilla%20European%20Options.ipynb)
		* [Speed Test](https://github.com/aschleg/IPython_Notebooks/blob/master/finance/Speed%20Test.ipynb)
		* [The Greeks](https://github.com/aschleg/IPython_Notebooks/blob/master/finance/The%20Greeks.ipynb)
* petpy
	- Vignette notebooks on using my [petpy](https://github.com/aschleg/petpy) library for working with the [Petfinder API](https://www.petfinder.com/developers/api-docs)
		* [Introduction to petpy](https://github.com/aschleg/IPython_Notebooks/blob/master/petpy/Introduction%20to%20petpy.ipynb)
		* [Download 45,000 Adoptable Cat Images with petpy and multiprocessing](https://github.com/aschleg/IPython_Notebooks/blob/master/petpy/Download%2045%2C000%20Adoptable%20Cat%20Images%20with%20petpy%20and%20multiprocessing.ipynb)
* poetpy
	- Series of notebooks introducing the functionality and some example use cases of the [poetpy](https://github.com/aschleg/poetpy) library.
		* [Introduction to Poetpy](https://github.com/aschleg/IPython_Notebooks/blob/master/poetpy/Introduction%20to%20Poetpy.ipynb)
		* [Building a Poetry Database in PostgreSQL with Python, poetpy, pandas and sqlalchemy](https://github.com/aschleg/IPython_Notebooks/blob/master/poetpy/Building%20a%20Poetry%20Database%20in%20PostgreSQL%20with%20Python%2C%20poetpy%2C%20pandas%20and%20sqlalchemy.ipynb)
* python_excel
	- Notebooks of using Python with Excel interactively. (Note: may be quite out of date at this point with the new releases of [xlwings](https://www.xlwings.org/)).
		* [Linear Regression with Python and Excel](https://github.com/aschleg/IPython_Notebooks/blob/master/python_excel/Linear%20Regression%20with%20Python%20and%20Excel.ipynb)
		* [Python-Excel_Data_Analysis](https://github.com/aschleg/IPython_Notebooks/blob/master/python_excel/Python-Excel_Data_Analysis.ipynb)
* AAC Shelter Pets Analysis
	- Series of notebooks that analyze the [Austin Animal Center's](http://www.austintexas.gov/department/aac) animal shelter [intakes](https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Intakes/wter-evkm) and [outcomes](https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Outcomes/9t4d-g238) dataset hosted on Socrata. 
		* [Austin Animal Center Intakes Exploratory Data Analysis](https://github.com/aschleg/IPython_Notebooks/blob/master/AAC%20Shelter%20Analysis/Austin%20Animal%20Center%20Intakes%20Exploratory%20Data%20Analysis.ipynb)
		* [From Intake to Outcome - Analyzing the Austin Animal Center's Intake and Outcomes Datasets](https://github.com/aschleg/IPython_Notebooks/blob/master/AAC%20Shelter%20Analysis/From%20Intake%20to%20Outcome%20-%20Analyzing%20the%20Austin%20Animal%20Center's%20Intake%20and%20Outcomes%20Datasets.ipynb)
		* [Shelter Cat Adoptions and Transfers Prediction Model](https://github.com/aschleg/IPython_Notebooks/blob/master/AAC%20Shelter%20Analysis/Shelter%20Cat%20Adoptions%20and%20Transfers%20Prediction%20Model.ipynb)
		* [Shelter Cat Outcomes - Exploratory Data Analysis](https://github.com/aschleg/IPython_Notebooks/blob/master/AAC%20Shelter%20Analysis/Shelter%20Cat%20Outcomes%20-%20Exploratory%20Data%20Analysis.ipynb)
		* [Shelter Cat Outcomes - Visualization of Data](https://github.com/aschleg/IPython_Notebooks/blob/master/AAC%20Shelter%20Analysis/Shelter%20Cat%20Outcomes%20-%20Visualization%20of%20Data.ipynb)
* Seattle Pet Licenses
	- Analysis of the Seattle Pet Licenses dataset available through Seattle's Open Data portal. The data is extracted with the Socrata Open Data Access (SODA) API using requests and then analyzed using a combination of pandas and seaborn.
		* [Extract and Analyze the Seattle Pet Licenses Dataset](https://github.com/aschleg/IPython_Notebooks/blob/master/Seattle%20Pet%20Licenses/Extract%20and%20Analyze%20the%20Seattle%20Pet%20Licenses%20Dataset.ipynb)

## Data

The data sets used in the notebooks will be listed here and can be downloaded from S3.

* [AAC Shelter Cat Outcomes](https://s3-us-west-2.amazonaws.com/animal-datasets/aac-shelter-outcomes/shelter+cats_data.tar.gz)
* [Seattle Pet Licenses](https://s3-us-west-2.amazonaws.com/animal-datasets/seattle-pet-licenses/seattle_pet_licenses.tar.gz)