# Seattle AirBnB Booking Analysis

## Table of Contents
1. [Installation](https://github.com/Olek-ua/Seattle_Project/tree/testing#installations)
2. [Project Motivation](https://github.com/Olek-ua/Seattle_Project/tree/testing#project-motivation)
3. [File Descriptions](https://github.com/Olek-ua/Seattle_Project/tree/testing#file-descriptions)
4. [Results](https://github.com/Olek-ua/Seattle_Project/tree/testing#results)
5. [Licensing, Authors, and Acknowledgements](https://github.com/Olek-ua/Seattle_Project/tree/testing#Licensing,-Authors,-and-Acknowledgement)

## Installations
You would need to install some of the standard data analysis & viz liabraries:

- numpy
- pandas
- matplotlib
- seaborn
- datetime

and for data modelling we will use only:

- scikit-learn

The easiest way to install package is using `pip`

`pip install -U <package name>`

or `conda`:

`conda install -c conda-forge <package name>`

make sure to replace `<package name>` with actual package name, like:

`conda install -c conda-forge scikit-learn`

## Project Motivation

In this project I wanted to practice CRISP-DM by exploring [Seattle Airbnb Open Data](https://www.kaggle.com/airbnb/seattle) from Kaggle. Primarily I'm looking to answer the following three business questions:

1. What is the busiest time of the year for Seattle?
2. What are the most expensive neighbourhoods?
3. Can we predict the price of a property based on its features?

Also I wanted to compare how does Linear Regression performs against Random Forest. The base for comparison would be RMSE and r-squared. After finding a winning model I will indentify the most important features of it.

## File Descriptions

- **Seattle AirBnB Bookings Analysis .ipynb** - is the main Jupyter file. You can get my results by simply running all lines in Jupyter notebooks. Beware the script may take some time (~20 min) to calculate the best performing model.

- **calendar.csv, listings.csv, reviews.csv** - are the files obtained from Kaggle. I've used only  calendar.csv and listings.csv in my research.

- **draft files** folder - this contains several Jupyter files which are simply separate steps of what was later combined in  **Seattle AirBnB Bookings Analysis** file, feel free to ignore this folder.

## Results

Please check my [Medium post - Use the power of Machine Learning to predict AirBnB prices in Seattle](https://medium.com/@oleksandr_49102/use-the-power-of-machine-learning-to-predict-airbnb-prices-in-seattle-bc9a781fd370) for full discussion of the project.

Here is the quick summary of what we've found in this project:

 - _On completion of Seattle AirBnB booking analysis we could clearly find the busiest time of the year in January, July and August._

- _With the most expensive neighbourhoods being Magnolia, Queen Anne and Downtown._

- _The strongest indicators of booking prices are cleaning fee, number of bathrooms and beds followed by minimum number of nights, room type, number of reviews and ofcourse neighbourhood._

## Licensing, Authors, and Acknowledgements

The content of this repository is licensed under a [Creative Commons Attribution License](https://creativecommons.org/licenses/by/3.0/us/)
