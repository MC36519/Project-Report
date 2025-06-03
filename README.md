# Project-Report
University of Macau – MSc in Data Science (AIA) by LEONG KA SENG (M-C3-6519-7)

### Project Objectives
This project proposes a machine learning-based Fault Detection and Diagnostics (FDD) model with knowledge enhancement for system-level HVAC chiller plants. The primary objective is to develop a hybrid method that combines physics knowledge and machine learning techniques for effectively identifying common but concealed faults in building energy management, particularly those caused by complex interactions within HVAC subsystems and hierarchical fault symptom patterns.  

This project involves developing a custom ensemble model based on hierarchical approach using a one vs. rest strategy. The multiple-class classification task will be divided into multiple binary classifiers, each trained on unique feature subsets for identifying one specific fault type. To enhance the model abilities, domain knowledge will be incorporated by deriving new features from physical principles and thermodynamic equations. Moreover, a high interpretability method of feature selection will be introduced, providing a high efficiency, interpretability, scalability, reproduction and flexibility approach for HVAC systems Fault Detection and Diagnostics.  

The performance of the proposed model will be evaluated against baseline models to ensure robustness and accuracy in fault detection and diagnostics. While the primary focus is on fault detection within the chiller plant, the methodology can provide insight and as a foundation for future work on other HVAC system-levels FDD.

### Hierarchical Model:
![image](https://github.com/MC36519/Project-Report/blob/main/Hierarchical%20Model.png)
