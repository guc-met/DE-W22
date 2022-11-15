# Data-Engineering-W22
This repository contains the notebooks for the Data Engineering course.

| Lab <br /> # | Topic | Lab <br /> Notebook | Exercise <br /> Solutions Notebook |
| --- | ----------- | ----- |----- |
| 1 | Explore Your Data| [Lab 1](https://github.com/guc-met/DE-W22/blob/main/Lab1/Lab_1.ipynb)  <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guc-met/DE-W22/blob/main/Lab1/Lab_1.ipynb)|
| 2 | Data Visualization| [Lab 2](https://github.com/guc-met/DE-W22/blob/main/Lab2/Lab_2.ipynb)  <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guc-met/DE-W22/blob/main/Lab2/Lab_2.ipynb)|[Lab 2 Solution](https://github.com/guc-met/DE-W22/blob/main/Lab2/Lab_2_Task.ipynb)  <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guc-met/DE-W22/blob/main/Lab2/Lab_2_Task.ipynb)|
| 3 | Data Visualization II| [Lab 3](https://github.com/guc-met/DE-W22/blob/main/Lab3/Lab_3.ipynb)  <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guc-met/DE-W22/blob/main/Lab3/Lab_3.ipynb)|[Lab 3 Solution](https://github.com/guc-met/DE-W22/blob/main/Lab3/Lab_3_Task.ipynb)  <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guc-met/DE-W22/blob/main/Lab3/Lab_3_Task.ipynb)|
| 4 | Data Cleaning| [Lab 4](https://github.com/guc-met/DE-W22/blob/main/Lab4/Lab_4.ipynb)  <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guc-met/DE-W22/blob/main/Lab4/Lab_4.ipynb)|[Lab 4 Solution](https://github.com/guc-met/DE-W22/blob/main/Lab4/Lab_4_Task.ipynb)  <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guc-met/DE-W22/blob/main/Lab4/Lab_4_Task.ipynb)|
| 5 | Data Transformation| [Lab 5](https://github.com/guc-met/DE-W22/blob/main/Lab5/Lab_5.ipynb)  <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guc-met/DE-W22/blob/main/Lab5/Lab_5.ipynb)|[Lab 5 Solution](https://github.com/guc-met/DE-W22/blob/main/Lab4/Lab_4_Task.ipynb)  <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guc-met/DE-W22/blob/main/Lab4/Lab_4_Task.ipynb)|


## Prerequisites
This repository requires that you have:-
* [Python3+](https://www.python.org/downloads/)
* [Numpy](https://numpy.org/install/)
* [Matplotlib](https://matplotlib.org/users/installing.html)
* [Seaborn](https://pypi.org/project/seaborn/)
* [Jupyter Notebook](https://jupyter.org/install)

### Installation of Prerequisites
#### Easy way (More HD space, less hassle)
Install [Anaconda](https://www.anaconda.com/products/individual) then just run Jupyter.

#### Hard way (Less HD space, more hassle)
Install [Python3+](https://www.python.org/downloads/) 

Make sure Python and pip are added to environment variables
![Python](https://bitsilla.com/wiki/lib/exe/fetch.php?w=600&tok=5a7732&media=images:py_setting_win.png)

From your Linux, Mac, or Windows terminal, verify that both are installed correctly.
```sh
$ python --version
$ pip --version
```

Using the same terminal install numpy, matplotlib, pillow and notebook
```sh
$ pip install numpy matplotlib pillow notebook
```

#### Alternative way (Cloud but you have to upload the data)
Click on the ![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg) next to the notebook you would like to exercise.

Upload the data needed as Data.zip using the following command
```
from google.colab import files
uploaded = files.upload()
```

Extract the zipped folder into the cloud using the following command
```
!unzip [foldername].zip
```

## How To Run
From your terminal, run this command then navigate to the *.ipynb* file you would like to exercise
```
jupyter notebook
```

## License
MIT License
