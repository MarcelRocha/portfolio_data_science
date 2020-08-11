
# Discover the best math notes from ENEM 2016

You must create a model to predict the grade of the math test of those who participated in ENEM 2016. For this, you will use Python, Pandas, Sklearn and Regression.


## Topics

In this challenge you will learn:

- Python
- Pandas
- Sklearn
- Regression

## Requirements

You will need python 3.6 (or higher) and the pip package manager.

It is recommended that you use a [virtual environment] (https://pythonacademy.com.br/blog/python-e-virtualenv-como-programar-em-ambientes-virtuais). To do this, execute the commands as in the example below:

Linux / macos

    pip3 install virtualenv
    virtualenv ../venv -p python3
    source ../venv/bin/activate 
    pip install -r requirements.txt

Windows

    pip3 install virtualenv
    virtualenv ..\venv -p python3
    ..\venv\Scripts\activate
    pip install -r requirements.txt


When you finish the challenge, you can leave the environment created with the command `deactivate`

## Details

The challenge context revolves around the results of ENEM 2016 (available in the file train.csv). This file, and only it, must be used for all challenges. Any questions about the columns, see the [Enem Microdata Dictionary 2016] (https://s3-us-west-1.amazonaws.com/acceleration-assets-highway/data-science/dicionario-de-dados. zip).

In the test.csv file, create a model to predict the grade of the math test (column `NU_NOTA_MT`) of those who participated in ENEM 2016.

Save your answer to a file called answer.csv with two columns: `NU_INSCRICAO` and` NU_NOTA_MT`.
