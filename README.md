#  HKUST CSIT5210 Group 4 Project  
Group Member: Yuan Fangxu, Guo Yuchen, Lin Lirong, Long Yuepeng, Lei Lijun


 Total vaccination data in US can be accessed from https://ourworldindata.org/covid-vaccinations#source-information-country-by-country
 
 Data pre-processing, description, goal 1 and goal 2 can be found in python code. 
 
 use data_cleaning.py to process [`2021VAERVAX.csv`](https://drive.google.com/file/d/1kcn6AVNoTtL-YYKk-lPNb1swMhxtpjcu/view?usp=sharing), [`2021VAERSYMPTOMS.csv`](https://drive.google.com/file/d/19o8ZtypcwSxIqTrQubD0ytvEjEMa0h-8/view?usp=sharing) and [`2021VEARSDATA`](https://drive.google.com/file/d/1IgXQzZPh-T-eFVPnkdBtAXB5knUtWwQv/view?usp=sharing) to get the [`data21.csv`](https://drive.google.com/file/d/1FOwvFU2brieaotQEIOgEKq7CgKKV1eAN/view?usp=sharing) .
 `data21.csv` is the dataset we used in the two assignments.
 Use the `SparsePCA1.ipynb` to do the Hospitalisation Prediction work.
 Use the `OnsetPrediction.ipynb` to do the Onset Time Prediction work.
 Use the `visual_1.ipynb` to do the Real Data Set Illness top-15 and Real data set length of stay work.
 Use the `visual_1.ipynb` to do the Proportion of three types of vaccination work.

## Final Report
1. Background  Lei
2. Introduction  Guo
3. Framework Lin
4. Hospital Prediction   Yuan
5. Onset Time Prediction   Long
6. Evaluation  Yuan, Long
7. Case Study  Yuan
8. Related Work  Lei
9. Discussion  Lin
10. Conclusion  Guo
11. Acknowledgement  


## CODE
336485 cases Date from 2021.1.1 to 2021.4.20
1. Hospitalisation Prediction  Yuan
* Sparse Naive Bayes
* Sparse Principal Component Analysis(PLA)+ logistic regression


Evaluation Criteria： 
* Optimal probability threshold 
* AUC 
* Training set sensitivity 
* Training set specificity 
* Validation set sensitivity 
* Validation set specificity

2. Onset Time Prediction   Long


* Random Forest(RF)
* Regularized regression(LASSO, RIDGE)
* Artificial neural network
* OLS

Evaluation Criteria：
* TrainingMSE
* TestMSE 
* Best predictors for shorter duration 
* Best predictors for longer duration

3. Data visualisation
* Proportion of three types of vaccination  Lei
* Real Data Set Illness top-15   Guo
* Real data set length of stay  Lin



