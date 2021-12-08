# Project Prevent

This repository contains the Python notebook and data necessary to run the notebook. We utilize difference-in-difference, Bacon Decomposition, the Callaway Method, Borusyak, Jaravel and Speiss (2021) estimator, and Causal Random Forest to evaluate whether state laws requiring or encouraging education on Child Sexual Abuse (CSA) in schools during the years 2005 through 2019 have an impact on reports of CSA. 

## Downloading Data

Before running the notebook, you will first need to download all the data we'll be using. This data is located in the folder `data`. When running the notebook you will upload all of the files in the `data` folder when the following line of code is run:

```python
uploaded = files.upload()
```

### Sample Data Note

We have provided two sample datasets of our CSA data where the variable names are the same as our original, however all the values are randomly generated. These files are called *sample_data_capstone.csv* and *sample_missing_reports.csv*. The data types in the sample sets match the original data types used. The original CSA data cannot be provided as it is IRB restricted. You can apply for access to the original data set or learn more at the [U.S. Department of Health & Human Services](https://www.acf.hhs.gov/cb/data-research/ncands).


## Dependencies

### System Dependencies

* [Python 3.7.12](https://www.python.org/downloads/release/python-3712/)

### Python Dependencies

To install python dependencies use the following command.

```bash
pip3 install --requirement requirements.txt
```

### Prompt When Installing Packages

When running the section in the notebook called *Install Packages and Import Libraries* the following line will prompt you to enter one or more numbers.

```bash
%%R
devtools::install_github("kylebutts/didimputation")
```

When you reach this, please enter the number `1`.

## Code

### Installing Anaconda

The easiest way to open the notebook is to utilize Anaconda. Follow the [installation instructions for Anaconda](https://www.anaconda.com/products/individual). 

After installing Anaconda you can open the code file *MasterProjectPrevent.ipynb*.

### Note

The last portion of the notebook is on social media analytics. However, this code will not run unless you have a Twitter API account. This portion of our analysis proved to not be fruitful and is not needed to recreate our results, but the code is provided for reference.