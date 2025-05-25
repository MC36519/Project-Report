# Dataset Information

**LBNL Fault Detection and Diagnostics Data Sets: Chiller Plant** by **Lawrence Berkeley National Laboratory (2022)**

Download link: <https://faultdetection.lbl.gov/dataset/simulated-chiller-plant/>

# Data Preparation
### Code Implementation Steps:

1. **Data Preparation**  
   1.1 Data Resampling  
   1.2 Labeling  
   1.3 Data Integration  

2. **Data Preprocessing**  
   2.1 Rectifying Features   
   2.2 Handling Noisy Data  

3. **Feature Engineering**  
   3.1 Standardizing Units  
   3.2 Deriving New Features  

4. **Output Data Files**  
   4.1 "df_faults_woF.xlsx": Original Feature Dataset (data cleaned but no new features added)  
   4.2 "df_faults_even.xlsx": Engineered Feature Set (with derived features) for **Main Project** use

# Useage
Due to file size limitations (>20 MB), the processed datasets were not uploaded to GitHub. However, you can follow the steps below to generate the datasets or download them from Google Drive:

Step1: Unzip the dateset file downloaded from [here](https://faultdetection.lbl.gov/dataset/simulated-chiller-plant/)  
Step2: Run the Data Preparation.ipynb  
Step3: You should get two data files: "df_faults_even.xlsx" and "df_faults_woF.xlsx" (See description above)  
Step4: If you fails to get those two data files, you may download it from Google Drive ["df_faults_even.xlsx"](https://docs.google.com/spreadsheets/d/1AoccNDYm5436xVN3hznnRqMH8FjG0NLg/edit?usp=drive_link&ouid=111681726938969201711&rtpof=true&sd=true) and ["df_faults_woF.xlsx"](https://docs.google.com/spreadsheets/d/1hUvhEX-Y6Eit7LgHHb8PQbXUHPt7WePf/edit?usp=drive_link&ouid=111681726938969201711&rtpof=true&sd=true)
