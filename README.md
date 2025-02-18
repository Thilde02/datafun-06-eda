

datafun-06-eda
This project is a custom exploratory data analysis project using many data analytics tools

Project set up
Using template based on previous projects I created and set up the project

Create repository in github named datafun-06-eda

Go to GitHub and log in.
Click the "+" in the upper-right corner and select New repository.
Name your repository datafun-06-eda.
Add a README.md file and choose a .gitignore template (Python).
Click Create repository.

Cloned down to local machine in VScode

cd ~
mkdir Projects
cd Projects
git clone (https://github.com/Thilde02/datafun-06-eda )
cd datafun-06-eda
code .

Added .gitignore and requirements.txt folders
created and activate virtual environment

  python -m venv .venv
  source .venv/bin/activate
  
Installed dependencies

py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt


 Install Required Packages

  pip install jupyterlab pandas seaborn matplotlib pyarrow
 
Create jupyter notebook tjh_eda.ipynb

Add markdown cell with title and purpose
Add code cell for imports

import pandas as pd
import seaborn as sns
import matplotlib
import jupyterlab
import pyarrow


Pull data set and test for confirmation

## Dataset: Netflix Titles
- **Source:** [Kaggle - Netflix Titles](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Description:** This dataset includes TV shows and movies available on Netflix with attributes such as title, director, cast, country, release year, rating, and more.



