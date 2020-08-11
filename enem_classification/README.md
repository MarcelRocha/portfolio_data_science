
# Find out who took ENEM 2016 just for training

In this challenge, find out which students are taking a test just for training.

## Topics

In this challenge you will learn:

- Python
- Pandas
- Sklearn
- Regression
- Classification

## Requirements

You have selected python 3.6 (or higher) and pip package manager.

To install the requirements, run the command as an example below:

    pip install -r requirements.txt


## Details

The challenge context revolves around the results of ENEM 2016 (available in the file train.csv). This file, and only it, must be used for all challenges. Any questions about the columns, see the [Enem Microdata Dictionary 2016] (https://s3-us-west-1.amazonaws.com/acceleration-assets-highway/data-science/dicionario-de-dados. zip).

Some students decide to take the ENEM test early, as a test (column IN_TREINEIRO). In this challenge, you must create a binary classification model to infer the same. The possible results of your answer must be "0" or "1".

Save your answer in a file called answer.csv with two columns: `NU_INSCRICAO` and` IN_TREINEIRO`.
