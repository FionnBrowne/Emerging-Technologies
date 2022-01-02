# Machine learning algothrims & Quantum computing
***
![Quantum Computer](https://akm-img-a-in.tosshub.com/sites/dailyo/fb_feed_images/story_image/201711/quantum-computers-fb_111117054856.jpg)

# List of contents
***

# What is this repository
***
## This repository contains lab work from my course Emerging technologies & my project on Scikit-Learn and Quantum computing. These notebooks demonstrate my work on the python packages `pandas` and `numpy,` which will be required to work with various algothrims on the jupyter notebook.

![Jupyter notebooks](https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/414px-Jupyter_logo.svg.png)

### This project containts two main [Jupyter notebooks](https://jupyter.org/):
    1.scikit-learn
    2.quantum-deutsch
    
### `scikit-learn` goes over various algothrims from sickit-learn [Machine Learning in Python](https://scikit-learn.org/stable/index.html). it also demonstrates some visualisation of data sets and gives some examples of why large companies use this site's algothrims.

### `quantum-deutsch` covers a comparison of quantum computing and classical computing, ranging from their similarities and differences. It then coveres Deutsch's algothrim [Deutsch-Jozsa Algorithm](https://qiskit.org/textbook/ch-algorithms/deutsch-jozsa.html), & simulates this using qiskit [Open-Source Quantum Development](https://qiskit.org/).

# Purpose of this repo:
***
### To demonstrate a deeper understanding of machine learning and quantum computing while learning how to use juypter labs with docker to provide a concise and easy-to-understand repository.

# Files:
***
### There are a few files required for this project in the Github repository, some of which can be edited by the user for more significant learning outcomes, such as the datasets.

## Datasets_CSV
***
### It contains the wine quality dataset, which is used for the sickit algothrims. You can download one of these datasets and then replace it with the wine quality and test out more algothrims. To get some more datasets, they can  
[be found on archive-beta](https://archive-beta.ics.uci.edu/ml/datasets), [Or on UCI machine learning](https://archive.ics.uci.edu/ml/index.php). 
### When downloading the datasets, you have to save them in this file to access them. To insert the new dataset into the jupyter notebook, you must enter something like this but make the path relative. Ex: 
`Users/NewRepoDatasets_CSV/winequality-red.csv` 

```python
# Load the data set from github url.
data = pd.read_csv("https://raw.githubusercontent.com/FionnBrowne/Emerging-Technologies/main/Datasets_CSV/winequality-red.csv", sep=";")

```

## Images
***
### It contains the images used in the notebooks and can be edited by the user at any point.


## Lab-work
***
### It contains all previous lab work done in this module that anyone can also glance over to understand the process better and see the development process.


## Sickit-Algothrims
***
### It is a Jupyter Notebook that contains three Sickit algothrims that use the datasets we import to perform such tasks as linear regression & correlation. It goes into detail about Sickit-learn and details on its use.


## Quantum-Computing
***
### It contains a clear and concise comparison of quantum computing and classical computing and explains Deutsch’s algorithm with code simulating it using Qiskit.


## Docker files 
***
### is a few files 
1. docker-compsoe.yml -> This Compose file defines the service web: The web service uses an image built from the Dockerfile in the current directory. It then binds the container and the host machine to the exposed port, 8888.

2. Dockerfile -> This file builds a `Docker image.` This image contains all the dependencies the Python application requires, including Python itself.

3. requirements.txt -> Contains any packages that need to be brought in through docker to run the notebooks. For this, we only have `qiskit[visualization].`

4. .dockerignore -> It prevents files from being added to the initial build context sent to the Docker daemon when you do docker build.


## Quick steps
***
### You can view the notebook in dynamic form by clicking the following image:
- Scikit-learn

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/FionnBrowne/Emerging-Technologies/blob/main/scikit-learn.ipynb)
- Quantum-deutsch

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/FionnBrowne/Emerging-Technologies/blob/main/quantum-deutsch.ipynb)

# Requirements
***
1. [Github](https://github.com/) account .
2. Download [Anaconda](https://docs.anaconda.com/anaconda/install/index.html).
3. Download [cmder](https://cmder.net/) if on Windows.
4. Download [Docker](https://docs.docker.com/get-docker/).
5. Configure your bios to allow WSL2.

# Getting ready.
***
1. Open cmd or the command prompt by going to the Windows search box and typing cmd.
2. In the command prompt/cmd, navigate to your desired location to save the files.
3. Create a file in the selected location by typing in: `$ mkdir fileNameHere`. 
4. Enter this file Ex: type `$ cd Users/NewRepo` for cmd or `$cd Users\NewRepo` for command prompt.
5. Enter the following command to clone the repository: `$ git clone https://github.com/FionnBrowne/Emerging-Technologies.git`

## How to run
***
1. First, navigate to repository location using either cmder or command prompt, for example: `$ cd Users/NewRepo/Emerging-Technologies`.
2. To run any of the notebooks, type `$ jupyter lab` in the current directory, or you could run the command `$ docker-compose up` to run it through Docker.

# Possible fixes for issues ???
1. Re-download this repository and make sure your on the right gile.
2. Check in task manager if WSL2 is enabled.
3. delete the previous files/images and re launch the program.

# Exploring
***
## You can mess around with the variables to see how it effects the visulization & data. Ex:  

```python
def f(x):
    return x*x

```

## Qiskit
![Qiskit Logo](https://qiskit.org/textbook/assets/images/logo_qiskit_purple_new.svg)

### I used the Qiskit textbook while creating this repository. You can find the link here: [Learn Quantum Computation using Qiskit](https://qiskit.org/textbook/preface.html).

# Learning outcome / conclusion
***

##


