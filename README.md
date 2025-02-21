# empirical_asset_pricing
In this project, we study using various machine learning models how the COVID pandemic affects share prices in tech stocks in the S&amp;P 500.

## Guide to our Github Repository 

To run the code, please either clone the repository using Git: 
``` 
git clone https://github.com/brandono7/empirical_asset_pricing.git 
```
or download the repository as a zip file and extract it to a location of your choice.

**Prerequisites**

Before running the project, make sure to install the following python libraries on your virtual environment via terminal / command prompt:

### Required Libraries
```
pip install -r requirements.txt
```

**Repository Structure**

1. **`src` folder**: Contains the essential Jupyter Notebooks used for data cleaning, analysis, model building - random walk, linear models, random forest and neural networks and the Diebold Mariano Test. This folder also contains the $R^2$ results for each model and the actual and predicted risk_premiums for the dm test in CSV files.
2. **`data` folder**: Contains the datasets that were used for this project.

This project is an assignment from a NUS course - DSE4101: Capstone Project in Data Science and Economics I.

Authors: Brandon, Nicholas, Yuchen

Special Thanks to Prof Liu Chunchun for her guidance. 

Last Updated: 21 Feb 2025