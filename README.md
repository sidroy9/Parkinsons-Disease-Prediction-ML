# Project: Parkinson's Disease Prediction Using ML
### Project Intro/Objective 

The purpose of this project is to predict whether a person is suffering from Parkinson's or not on the basis of his/her input data. The prediction has been done by using Machine Learning (ML) classification algorithm.

### Install

This project requires **Python** and the following Python libraries installed:

- NumPy
- Pandas
- matplotlib
- Seaborn
- scikit-learn

You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, you can install the Anaconda distribution of Python, which already has the above packages and more included. 

### Code

Code is provided in the `Parkinsons_Disease_Prediction.ipynb` notebook file. You will also be required to use the `ParkinsonsDisease.csv` dataset file to complete your work.

### Run

In a terminal or command window, navigate to the top-level project directory `Parkinsons-Disease-Prediction-ML/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Parkinsons_Disease_Prediction.ipynb
```  
or
```bash
jupyter notebook Parkinsons_Disease_Prediction.ipynb
```
or open with Jupyter Lab
```bash
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The ParkinsonsDisease dataset consists of 195 data points, with each datapoint having 22 features. This dataset is Parkinsons Disease Dataset found on the kaggle.

**Features**
1. `MDVP:Fo(Hz)`: Average vocal fundamental frequency
2. `MDVP:Fhi(Hz)`: Maximum vocal fundamental frequency
3. `MDVP:Flo(Hz)`: Minimum vocal fundamental frequency
4. `MDVP:Jitter(%)`
5. `MDVP:Jitter(Abs)`
6. `MDVP:RAP`
7. `MDVP:PPQ`
8. `Jitter:DDP`: Several measures of variation in fundamental frequency
9. `MDVP:Shimmer`
10. `MDVP:Shimmer(dB)`
11. `Shimmer:APQ3`
12. `Shimmer:APQ5`
13. `MDVP:APQ`
14. `Shimmer:DDA` :Several measures of variation in amplitude
15. `NHR`
16. `HNR`: Two measures of ratio of noise to tonal components in the voice
17. `RPDE`
18. `DFA`: Signal fractal scaling exponent
19. `spread1`
20. `spread2`
21. `PPE`: Three nonlinear measures of fundamental frequency variation
22. `D2`: Two nonlinear dynamical complexity measures


**Target Variable**
23. `status`: Class variable (0 or 1) 147 of 195 are 1, the others are 0. Value 1 - Parkinson's, 0 - healthy