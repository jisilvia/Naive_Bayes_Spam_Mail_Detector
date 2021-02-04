# Spam eMail Detection using Naive Bayes Classification Algorithm
<p align="center">
  <img width="460" height="300" src="https://emailchef.com/wp-content/uploads/2019/06/email-spam-reputation-636x425.png">
</p>

In statistics, naive Bayes classifiers are a family of simple "probabilistic classifiers" based on applying Bayes' theorem with strong independence assumptions between the features. They are among the simplest Bayesian network models, but coupled with kernel density estimation, they can achieve higher accuracy levels.


# Project Description

In this project, a model is trained with set of emails labelled as either from Spam or Non-Spam. There are 702 emails equally divided into spam and non spam category. Next, the model is tested on 260 emails. The model is tasked to predict the category of the emails and compare the accuracy with known correct classifications. There are two folders: test-mails and train-mails. Train-mails are to train the model. Test-mails are used to test the accuracy of the model. Each email's first line is the subject; the content starts from the third line.

## Steps

 1. Cleaning and Preparing Data
 2. Building the Algorithms
 3. Training and Predicting Results
 4. Evaluation

## Requirements

**Python.** Python is an interpreted, high-level and general-purpose programming language. 

**[Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true).** Google colab is a free online Integrated Data Environment.

### Packages 
Install the following packages in Python prior to running the code.
```python
import os
import numpy as np
from collections import Counter
from sklearn.naive_bayes import GaussianNB
from sklearn.metrics import accuracy_score
from google.colab import drive
drive.mount('/content/drive')
```
After importing ```drive.mount('/content/drive')```, follow instructions in the output to authorize access to Google Drive in order to obtain directories.

## Launch

Download the data file provided and decompress it. Using Google Drive, create the following folder structure and upload the data here:

```
/content/drive/MyDrive/MSBA_Colab_2020/ML_Algorithms/CA02/Data
```

where ```/content/drive/MyDrive``` is the standard file path.

## Authors

[Silvia Ji](https://www.linkedin.com/in/silviaji/) - [GitHub](github.com/jisilvia)

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

## Acknowledgements

The project template and dataset were provided by [Arin Brahma](https://github.com/ArinB) at Loyola Marymount University.
