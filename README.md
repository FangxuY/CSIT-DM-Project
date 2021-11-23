#  HKUST CSIT5210 Group 4 Project  
Group Member: Yuan Fangxu, Guo Yuchen, Lin Lirong, Long Yuepeng, Lei Lijun


 Total vaccination data in US can be accessed from https://ourworldindata.org/covid-vaccinations#source-information-country-by-country
 
 Data pre-processing, description, goal 1 and goal 2 can be found in python code. 
 
 use data_cleaning.py to process [`2021VAERVAX.csv`](https://drive.google.com/file/d/1kcn6AVNoTtL-YYKk-lPNb1swMhxtpjcu/view?usp=sharing), `2021VAERSYMPTOMS.csv` and `2021VEARSDATA` to get the `data21.csv` .
 data21.csv is the dataset we used in the tuo

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
* Sparse Principal Component Analysis(PLA)+ logistic regression(existed)


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

3. 数据可视化
* 三种疫苗接种比例  Lei
* 真实数据集病症top-15   Guo
* 真实数据集住院时间  Lin



