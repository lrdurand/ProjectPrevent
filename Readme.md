# Project Prevent

This repository contains the Python notebook and data necessary to run the notebook. We utilize difference-in-difference, Bacon Decomposition, the Callaway Method, and Causal Random Forest to evaluate whether state laws requiring or encouraging education on Child Sexual Abuse (CSA) in schools during the years 2005 through 2019 have an impact on reports of CSA. 

## Downloading Data

Before running the notebook, you will first need to download all the data we'll be using. This data is located in the folder `data`. When running the notebook you will upload all of the files in the `data` folder when the following line of code is run:

```python
uploaded = files.upload()
```

### Sample Data Note

We have provided a sample dataset of our CSA data where the variable names are the same as our original, however all the values are randomly generated. The data types in the sample set match the original data types used. The original CSA data cannot be provided as it is IRB restricted. You can apply for access to the original data set or learn more at the [U.S. Department of Health & Human Services](https://www.acf.hhs.gov/cb/data-research/ncands).


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

Use the following to access our code in Google Colab.

* Insert colab link here 
* Or provide further info on how to open if we share the notebook in another format.