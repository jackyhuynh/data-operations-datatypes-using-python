# Data Types and Data Operation Using Python

## Introduction

Data Mining using Python is a set of lesson that introduce to Data Mining using Python. This is the first serial which includes:
- Data pre-processing
  - Dimensionality reduction
  - Sampling
  - Feature reduction

## Sampling
- Identify statistically significant
- Watch out for data bias
- Try to understand the data source
- Sample must present whole population to avoid bias
- Limiting analyst a subset of data

## Why Sampling?
- Processing all data can be costly
- Type of sampling:
  - Progressive Sampling: Sampling until sufficient
  - Backed test biases: Using historical data to predict how well it will do in the future

## Feature Selection:
- Technique for data preprocessing
- Feature, attribute vs. variable: column in our dataset
- Feature is often used when talking about removing, creating, or transforming attributes
- Selecting a subset of attributes to improve the performance of a learning algorithm
- reduce the dimensionality of the data
- Redundant feature: duplicate feature
- Irrelevant Feature: contain no information that is useful for the data mining task
- Embedded based: Feature selection occurs naturally as part of the data mining algorithm
  - Example: Decision Tree
- Filter based: Feature are selected before data-mining algorithm is running
  - Example: Correlation-based feature selection
- Wrapper based: Use the data-mining algorithm as a black box to find the best subset attributes
  - Example: Brute force feature selection

## Dimensionality Reduction:
- Dimensionality: number of attributes in a datasets
- As dimensionality increase, data becomes more spare (difficult to clustering and meaningful measure distance)

## Feature Creation:
- Feature extraction (domain expect)
- Feature construction

## Attribute Confirmation:
- z score value, Mean, Standard deviation
- Z score use before performing PCA, before calculating a distance measure
- Z-score Normalization can affect by Outliers

## Exploratory Data Analysis


## Resources:
- [Python 3 Standard Library](https://docs.python.org/3/index.html)
- [NumPy Reference Document](https://numpy.org/doc/stable/reference/index.html)
- [Pandas Document](https://pandas.pydata.org/docs/)
- [Matplotlib Document](https://matplotlib.org/2.0.2/index.html)
- [Scikit-Lean Document](https://scikit-learn.org/stable/modules/classes.html)

## Technology
List of technology
- Python 
- Object Oriented Design
- Jupyter Notebook
- Data Visualization
- Machine Learning

## Python for Data Science Tools:
These are packages that are usually used for Data Science:
- [Python 3 Standard Library](https://docs.python.org/3/index.html)
- [NumPy Documentation](https://numpy.org/doc/stable/reference/index.html)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Mathplotlib Documentation](https://matplotlib.org/2.0.2/index.html)

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
What things you need to install the software and how to install them
- Jupyter Notebook: If you want just test the code, simply go to google and search for jupiter notebook or another Python online IDE. The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. 
- Anacoda Navigator: Install Anaconda Navigator if you want to develop data-science projects using Python or R. Anaconda Navigator is a desktop graphical user interface included in Anaconda that allows you to launch applications and easily manage conda packages, environments and channels without the need to use command line commands. 

### Installing
A step by step series of examples that tell you how to get a development enviroment running
* [Install Anacoda Navigator](https://docs.anaconda.com/anaconda/navigator/install/#:~:text=Installing%20Navigator%20Navigator%20is%20automatically%20installed%20when%20you,install%20anaconda-navigator.%20To%20start%20Navigator,%20see%20Getting%20Started.) - If you haven't downloaded and installed Anacoda Navigator yet, here's how to get started.
* [Jupyter Notebook](https://jupyter.org/try) - Click here to go to the online free Jupiter Notebook.

## Running the tests
Explain how to run the automated tests for this system:
- There is no download IDE need, all you need is download all the src to your machine and run it.
- Using Jupiter Notebook
- Navigate to the file .ipynb
- hit:
```
Ctrl + Enter
```

## Deployment
All the notebook can be used for research and academic basic function for Python. 

## Built With
* [Jupyter Notebook](https://jupyter.org/try) 

## Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](). 

## Authors

* **Truc Huynh** - *Initial work* - [TrucDev](https://github.com/jackyhuynh)

## Format
my README.md format was retrieved from
* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
* Any acknowledgments go here
