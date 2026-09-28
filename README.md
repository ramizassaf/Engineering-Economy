# Project Title

Engineering Economy Ranking and IRR Methods Analysis

## Project Description & Features

The Project performs the Ranking Methods {[present worth analysis], [future worth analysis], [annual worth analysis]}, and the IRR [Internal Rate of Return] for a given project.

The project has three main features:
1. The project plots the Cash Flow Diagram for each Alternative Data, you can update the data in the files in the directory <../data>.
2. The project performs the ranking methods mentioned above and IRR.
3. The project gives a conclusion about the recommended alternative to go for.

### Prerequisites

you need install the following dependencies: 

```
Python
pip
numpy-financial
matplotlib
```

### Installing

python installation

```
$ sudo apt-get update
$ sudo apt-get install python3.6
```

pip installation

```
$ sudo apt update
$ sudo apt install python3-pip
```

numpy-financial installation (NumPy removed its financial functions in version 1.20)

```
$ pip3 install numpy-financial
```

matplotlib installation
```
$ sudo apt update
$ sudo apt upgrade
$ sudo apt install python3-matplotlib
```

## Running the tests

run the file project.py in the directory <../src> (works from any directory)
```
$ python3 src/project.py
```

Enter MARR as a decimal, for example 0.1 for 10%.
