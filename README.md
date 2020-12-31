# AS24 Assignment
#### Assignment Snippets:
>Attached to this email you'll find two CSV files. One with data on AS24 listings and another one describing the columns.
For the case study we want you to explore the data and investigate two questions:
    1. Is it possible to predict the product tier from the information given in the other columns?
    2. Is it possible to predict detail views from the information given in the other columns?
    
>Please prepare a Jupyter Notebook to share your results and thoughts with us. We're not just looking at how well you can model the data but are also interested in your general approach and thoughts on the data and potential algorithms. So please document your code and communicate your results using markdown cells.

### Libraries Used

The given notebook uses the below libraries in Python:
* Tensorflow - *For Neural Network modelling*
* Scikit-Learn - *For all our ML needs*
* Pandas - *To load, analyse and explore the data as dataframe*
* Matplotlib & Seaborn - *To visualize the data using bar plots, desnsity plots and more*

### Installation

This notebook requires Python 3.7+ to run.

Create a virtual environment, install the dependencies and start the Jupyter Server.

```sh
$ cd AS24
$ pip install virtualenv
$ virtualenv venv
$ venv\Scripts\activate
$ pip install -r requirements.txt
$ python -m ipykernel install --user --name venv --display-name venv
$ jupyter notebook
```
