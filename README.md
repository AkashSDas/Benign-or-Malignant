# Benign or Malignant

  

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/AkashSDas)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/AkashSDas)

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)

  
  

## Table of contents

  

*  [About](#about)

* [What are Tumor, Benign and Malignant?](#terms)

* [Technologies Used](#technologies-used)

* [Results of the Project](#results-of-the-project)

*  [Installation](#installation)

*  [Acknowledgments](#acknowledgments)

*  [Data Source](#data-source)

*  [License](#license)

  
  

## About

> Machine Learning and Data Science are paving the way for predictive analysis, something which offers insights into a patient’s health state, say, 9-10 years down the line.

> If we are able to about  tell with a high **possibility** that what type of **tumor** does a patient have then right measures can be taken in order to save his/her life.

> In this project using using techniques likes `embedded method` and `backward elimination` for feature selection. After selecting features `Classification` models are used and `cross validation` is done. `Learning Curve` is evaluated to see if the model is working correctly, after that `parameter tuning` is done followed by cross validation and then model is trained with the training data. At last model is tested on the test data and is `evaluated` on the basis of `precision`, `recall` and `f1-score`.


## Terms

#### What are Tumor, Benign and Malignant?

> **`Tumor`**: A tumor is an abnormal lump or growth of cells. When the cells in the tumor are normal, it is benign. Something just went wrong, and they overgrew and produced a lump. When the cells are abnormal and can grow uncontrollably, they are cancerous cells, and the tumor is malignant.

> **`Benign`**: If the cells are not cancerous, the tumor is benign. It won't invade nearby tissues or spread to other areas of the body metastasize. A benign tumor is less worrisome unless it is pressing on nearby tissues, nerves, or blood vessels and causing damage.

>**`Malignant`**: Malignant means that the tumor is made of cancer cells, and it can invade nearby tissues. Some cancer cells can move into the bloodstream or lymph nodes, where they can spread to other tissues within the body2—this is called metastasis. Cancer can occur anywhere in the body including the breast, intestines, lungs reproductive organs, blood, and skin.

## Technologies Used
  
> [![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/) is used as Programming Language.

>  `Numpy` is used for the mathematical and data manipulation.

>  `Pandas` is used to analysis and manipulation of data.

> `Matplotlib` and `Seaborn` are used for data visualisation which helped in the analysis of data.

> `Statsmodels` is used to perform statistical test and data exploration.

> `Sciki-learn` is used for data preprocessing, creating machine learning model and evaluating it, thus creating a pipeline.

> `Pipenv` is the virtual environment used for the project. `Jupyter Notebook` is used to for the entire data science and machine learning life cycle.

## Results of the Project

#### Correlation Matrix

![Correlation Matrix](https://github.com/AkashSDas/Benign-or-Malignant/blob/master/project-results-images/correlation-matrix.png)

#### Feature Section using embedded method results

![Lasso Model Results](https://github.com/AkashSDas/Benign-or-Malignant/blob/master/project-results-images/feature-selection-using-lasso-model.png)

#### Learning Curve

![Learning Curve](https://github.com/AkashSDas/Benign-or-Malignant/blob/master/project-results-images/leraning-curve.png)

####  Metrics Scores

![Metrics Scores](https://github.com/AkashSDas/Benign-or-Malignant/blob/master/project-results-images/metrics-scores.png)

#### Confusion Matrix

```python
  precision    recall  f1-score   support

           2       0.97      0.94      0.95       132
           4       0.90      0.95      0.92        73

    accuracy                           0.94       205
   macro avg       0.93      0.94      0.94       205
weighted avg       0.94      0.94      0.94       205
```

![Confusion Matrix](https://github.com/AkashSDas/Benign-or-Malignant/blob/master/project-results-images/confusion-matrix.png)



## Installation

  

It is highly **recommended** to use **`virtual environment`** for this project to avoid any issues related to dependencies.

  

Here **`pipenv`** is used for this project.

  

There is a **`requirements.txt`** file in `'Benign-or-Malignant'/requirements.txt` which has all the dependencies for this project.

  

- First, start by closing the repository

  

```bash

git clone https://github.com/AkashSDas/Benign-or-Malignant

```

  

- Start by installing **`pipenv`** if you don't have it

```bash

pip install pipenv

```

  

- Once installed, access the venv folder inside the project folder

```bash

cd  'Benign-or-Malignant'/venv/

```

  

- Create the virtual environment

```bash

pipenv install

```

The **Pipfile** of the project must be for creating replicating project's virtual environment.

  

This will install all the dependencies and create a **Pipfile.lock** (this should not be altered).

  

- Enable the virtual environment

```bash

pipenv shell

```

  

- dataset, jupyter notebook and model are in `'Benign-or-Malignant'/requirements.txt/src` folder.

  

```bash

cd src/

```

  

- To start/view the jupyter notebook

```bash

jupyter noterbook

```

  

This will open a webpage in the browser from there you can click on notebook.ipynb to view it.

  
  

## Acknowledgements

  

All the rights of the Data are bound to the ISIC-Archive rights <a  href='https://www.isic-archive.com/#!/topWithHeader/wideContentTop/main'>source</a>. I do not take any responsibility for the right-infringement of any kernels. Thus, do not monetize this any of your models done on this data.

  

## Data Source

  

The [source](https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign) of the data is Kaggle.

  

## License

  

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.
