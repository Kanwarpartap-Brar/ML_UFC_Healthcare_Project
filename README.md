README.txt: Machine Learning Model Evaluation (UFC & Healthcare Datasets)

By: Kanwarpartap Brar

--------------------------------------------------------------------------------------
Overview:
This project evaluates 8 machine learning models on 2 datasets:
- UFC Fight Dataset (Binary Classification)
- Healthcare Dataset (Multi-class Classification)

Each model has:
- Preprocessed Data
- Hyperparameter Tuning 
- Model evaluation using accuracy score, classification report, and confusion matrix
- Hyper-parameter Tuning Plots & Confusion Matrix visualization plots

--------------------------------------------------------------------------------------
Code.zip Contains:

*******Execution******
- main.py

*****UFC Files*****
UFC py files:
- UFC_Decision_Tree.py
- UFC_Logistic_Regression.py
- UFC_SVM.py
- UFC_Ensemble.py
- fight_utils.py (contains functions to process UFC fight vector)

*****Healthcare Files*****
Healthcare py files:
- healthcare_KNN.py
- healthcare_perceptron.py
- healthcare_SVM.py
- healthcare_ensemble.py

*****CSV Data Files*****
- UFC_Train_Data.csv
- UFC_Test_Data.csv
- complete_fighter_statistics.csv
- cleaned_healthcare_train.csv
- cleaned_healthcare_test.csv

*****Graphs Folder*****
- Plots folder contains all visualizations for the 8 models

--------------------------------------------------------------------------------------
REQUIRED LIBRARIES:

- Pandas
- NumPy
- MatPlotLib
- Seaborn
- Scikit-Learn

--------------------------------------------------------------------------------------
RUNNING THE CODE:

1. Unzip the Code.zip file

2. At the Code folder open a new terminal by right clicking

3. Run python main.py

- This will train and evaluate all 8 models and display 2 visualization for each model (the hyper parameter tuning plot & confusion matrix)

- This will also display the accuracy score and classification report for each model

- For most of the models this will also go through the cross validation 

****IMPORTANT DISCLAIMER*****

- Some of the models take a long time to run, specifically the SVM model for the healthcare dataset. 

- The UFC dataset models do not take too long, however the healthcare dataset models may take about 10 minutes to all run. 

- The program will stop once all 8 models have run and all the visualizations are displayed

*****TIP*****
On Mac sometimes the file will stop running unless you close the figure windows which display the visualization for the models. If the program stops running try and closing the visualization windows and it should continue. 

