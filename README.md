# Spam eMail Detection using Naive Bayes Classification Algorithm
![enter image description here](https://emailchef.com/wp-content/uploads/2019/06/email-spam-reputation-636x425.png)

In statistics, naive Bayes classifiers are a family of simple "probabilistic classifiers" based on applying Bayes' theorem with strong independence assumptions between the features. They are among the simplest Bayesian network models, but coupled with kernel density estimation, they can achieve higher accuracy levels.


# Project Description

In this exercise we shall train the model with set of emails labelled as either from Spam or Not Spam. There are 702 emails equally divided into spam and non spam category. Next, we shall test the model on 260 emails. We shall ask model to predict the category of this emails and compare the accuracy with correct classification that we already know.

## Steps

 1. Cleaning the Data
 2. Extracting features and corresponding label matrix
 3. Training and predicting with sklearn Naive Bayes
 4. Accuracy Score
 5. Conclusion

## Requirements

**Python.** Python is an interpreted, high-level and general-purpose programming language. 

**[Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true).** Google colab is a free online Integrated Data Environment.

### Packages 
Install the following packages in Python prior to running the code.
```python
import pandas as pd
import numpy as np
from sklearn.impute import SimpleImputer
import matplotlib.pyplot as plt
```

## Launch

Download the data file provided and decompress it. Using Google Drive, create the following folder structure and upload the data here:

```python
/content/drive/My Drive/MSBA_Colab_2020/ML_Algorithms/CA02/Data
```

## Authors

[Silvia Ji](https://www.linkedin.com/in/silviaji/) - [GitHub](github.com/jisilvia)

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

## Acknowledgements

The project template and dataset were provided by [Arin Brahma](https://github.com/ArinB) at Loyola Marymount University.
