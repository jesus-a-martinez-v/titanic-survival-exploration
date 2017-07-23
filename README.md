# Titanic Survival Exploration

![alt tag](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/1280px-RMS_Titanic_3.jpg)

A brief exploration of the survival data of passengers of the RMS Titanic. The main goal is to gain insight by developing several predictors that rely on more complex and informative features. The whole notebook can be reviewed [here](https://github.com/jesus-a-martinez-v/titanic-survival-exploration/blob/master/titanic_survival_exploration.ipynb). This project was developed as part of the amazing [Machine Learning Engineer Nanodegree offered by Udacity](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009).


## Software Requirements
This project uses the following software and Python libraries:

- [Python 3.6](https://www.python.org/downloads/release/python-360/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).


If you already have Python 3.6 installed on your computer, then you can install `numpy`, `pandas`, `matplotlib` and Jupyter Notebook (formerly known as "iPython") by using [pip](https://pip.pypa.io/en/stable/) on the command line. [This page](http://www.lfd.uci.edu/~gohlke/pythonlibs/) may also be of use for some packages for Windows users, if pip has trouble performing the installation. After installing pip, you can install all the packages with the following command:

`sudo pip install numpy pandas matplotlib jupyter`

### Data

The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and contains the following attributes:

**Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)
