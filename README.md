# Maximizing Performance: Data Analysis of Formula 1 Driver and Race Data
[<img width="1200" alt="Screenshot 2023-04-04 at 7 48 02 AM" src="https://user-images.githubusercontent.com/99470852/229669829-7762e338-5e22-4e40-9e0a-3ab8d479b0db.png">
](https://private-user-images.githubusercontent.com/125974130/363682426-6a34d27e-bd9e-4a0b-ae35-b460bfd55b6b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjYyMTg0MzEsIm5iZiI6MTcyNjIxODEzMSwicGF0aCI6Ii8xMjU5NzQxMzAvMzYzNjgyNDI2LTZhMzRkMjdlLWJkOWUtNGEwYi1hZTM1LWI0NjBiZmQ1NWI2Yi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTEzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkxM1QwOTAyMTFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00MDFmMDliMGZmMDE4ODE1YjgyY2JlOTUxMzE2YTUyOTdiNWUwNGQ5MTVjZDJhMGY3MTM2Y2IzNmE2ZDg1NjgwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.NSZZ_xpHGVOPw0nMfC67VnMPClwVuACZWi0vUcM2a2o)
## Introduction

The Formula 1 (F1) racing championship is a highly competitive motorsport that generates vast amounts of data during races, including telemetry data from cars, performance data, driver information, and race results. This project aims to harness the power of data analysis techniques to gain deeper insights into F1 data, unlocking its full potential for improving team performance, optimizing race strategies, and enhancing overall race outcomes.
This repository contains data analysis of Formula One (F1) races.The data is accurate as of the 2023 Bahrain Grand Prix. The analysis is performed using Python programming language and various data analysis libraries such as Pandas, Numpy, and Matplotlib.



## Data Source
The data is obtained from Kaggle, which is a platform for data science competitions. The dataset contains information about F1 drivers , seasons competed , race data and points earned.



## File Structure
- F1DriversDataset 2.csv - contains the raw dataset in CSV format
- f1.ipynb - Jupyter notebook used for data analysis
- plots - directory containing plots generated from data analysis
- README.md - this file



## Data Cleaning
The raw dataset contains missing values and inconsistent data types. Data cleaning is performed using Pandas library to remove missing values and convert data types to the appropriate format for data analysis.



## Data Analysis
The data is analyzed to find insights and answer various questions related to F1 races. The analysis includes correlation analysis, and visualization using Matplotlib library.



the questions explored here are :

1. what is the distribution of driver nationalities in this dataset?
2. What is the correlation between the number of seasons a driver participates in and their number of race wins?
3. What is the correlation between the number of podium finishes and the number of pole positions for drivers who are/have been champions?
4. what does it take to be a champion?



## Conclusions
The data analysis reveals interesting insights about F1 races, the drivers who compete(d) and championships won. The findings are summarized in the Jupyter notebooks and visualized in the plots directory.



## References
Kaggle dataset: https://www.kaggle.com/datasets/dubradave/formula-1-drivers-dataset

Pandas documentation: https://pandas.pydata.org/docs/

Matplotlib documentation: https://matplotlib.org/stable/contents.html
