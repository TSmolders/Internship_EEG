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

Analytical pipeline overview:
![image](https://github.com/TSmolders/Internship_EEG/assets/158051735/fc202056-f5ef-43fb-9d03-9ff5e9620555)
Boxes represent objects within pipeline. General analytical approaches and direction are represented with solid arrows. Dashed arrows show specific steps within general approaches. Parts of the pipeline that were performed with the TDBRAIN code or the MNE toolbox have been encased in respectively labeled boxes. EEG = electroencephalography; TFR = time-frequency representation; FC = functional connectivity; GCN = graph convolutional network; ML = machine learning; cv = cross-validation.
