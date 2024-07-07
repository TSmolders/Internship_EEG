# Internship_EEG
 Predicting psychiatric diagnosis with EEG recordings obtained from the TDBRAIN dataset.

 Evaluating performance of multiple EEG-features and multiple Machine/Deep learning models to predict psychiatric diagnosis.
 
 Student: Tuur Smolders
 
 Supervisor: Dr. Marijn van Wingerden

Included in the investigation:
- standard ML models: Random Forest, Support Vector Machine, Gradient Boosting Classifier
- Graph Neural Networks: standard Graph Convolutional Network, graphLambda without edge attributes, graphLambda with edge attributes
- Feature sets: 1) statistical Time-Frequency representation (TFR) features (statistical measurements [mean, std, median, skew, kurt] of power over time], 2) stat TFR features + functional connectivity features)
- Feature sets derived from: eyes-open en eyes-closed resting-state EEG data, and the ratio between eyes-closed divided by the eyes-open resting-state EEG data.

Analytical pipeline is shown in order of the notebooks. Notebooks containing code for background information can be found in the 'background_notebooks' subdirectory.
