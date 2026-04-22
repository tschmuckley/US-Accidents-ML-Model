# US-Accidents-ML-Model
This is our final project for CSCI4622

## By Austin McCutcheon and Trevor Schmuckley
## 04/24/2026

# US Accidents Severity and Risk Project

## Project Description
The first part of this project uses Random Forests using a accident dataset found on Kaggle to help predict accident
severity. The second part of this project uses HistGradientBoostingClassifier to try and predict risk
of driving in different environment such as location, population, weather, and time of day.
Warning this second section of the project uses synthetic data therefore should not be used fore real
world risk assement.

## Files included in submission
- README.md: This gives a basic description of the project and its dependencies.
- US_Accidents_ML_Model.ipynb: This is where you can find the code used to generate our model.
- ML Project Report.PDF: This is where you can find the report containing a summerized review of our
project

## Dependencies
- `pandas` — data loading and preprocessing
- `numpy` — numerical operations
- `matplotlib` — plotting and visualization
- `scikit-learn` — machine learning models for random Forests and HistGradientBoostingClassifier
- `census` — access to U.S. Census API data
- `us` — helper library for working with U.S. geographic/state information
- `pgeocode` — ZIP code lookup for latitude and longitude
- `google Colab` — best environment for running notebook

## Steps to run notebook
1. Download US_Accidents_ML_Model.ipynb.
2. Run the notebook using Colab you will need to run the notebook using the most powerful chip avalible
since lesser chips take 4-40+ hours to run.
3. Setup google drive to store Random Forest model this is important since not doing so will cause
the user to run out of RAM and Colab will crash.
4. Click run all cells and wait.

## Important Consideration About our Model
- The second section of the notebook uses synthetic data thus any output that the user gets from this
model should 

**NOTE:** The Jupyter notebook may take up to 45 minutes using Colab's High RAM environment due to certain model parameters. For ease of grading, we have added a PDF copy of the program to the main folder with our last run completed before this submission. We hope this helps.

90% of the grading criteria will be copied from the notebook to this Readme file to fulfill the grading requirements put forward in Prof. Velasquez' announcement on 4/7.

This project was originally built using IntelliJ's Idea in a Jupyter notebook. After waiting for 40 hours for a run to finish, Trevor learned about Google Colab and we shifted gears to using it exclusively to run the project.

