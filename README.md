#  HKUST CSIT5210 Group 4 Project  
Group Member: Yuan Fangxu, Guo Yuchen, Lin Lirong, Long Yuepeng, Lei Lijun


 VAERS Data were compressed in vaers.rar 
 
 Total vaccination data in US can be accessed from https://ourworldindata.org/covid-vaccinations#source-information-country-by-country
 
 Data pre-processing, description, and goal 1 can be found in R code. Goal 2 can be found in python code. 

Final Report
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


实验代码：
632396 cases
1. Hospitalisation Prediction
* Sparse Naive Bayes
* Linear Discriminant Analysis (LDA)
* Locally linear embedding (LLE)
* Laplacian Eigenmaps
* Sparse Principal Component Analysis(PLA)+ logistic regression(existed)
* Plain Bayes classifier + Laplace smoothing (existed)
* (Singular Value Decomposition)SVD

Evaluation Criteria： yuan
* Optimal probability threshold 
* AUC 
* Training set sensitivity 
* Training set specificity 
* Validation set sensitivity 
* Validation set specificity

2. Onset Time Prediction   long
Random Forest(RF)
Regularized regression(LASSO, RIDGE)
Artificial neural network
OLS

Evaluation Criteria：
* TrainingMSE
* TestMSE 
* Best predictors for shorter duration 
* Best predictors for longer duration

3. 数据可视化
* 三种疫苗接种比例  Lei
* 真实数据集病症top-15   Guo
* 真实数据集住院时间  Lin

数据：
date_vax 接种时间 
Date 发病时间
dur 
Allergic - AF 既往病史
SYMPTOM1-5 病症
manu： MODERNA = 0, PFIZER\BIONTECH = 2, JANSSEN = 3


