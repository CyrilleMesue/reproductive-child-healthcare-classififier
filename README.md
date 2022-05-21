# Reproductive Child-Healthcare Classification
The data was provided by DPhi through Reproductive Child-Healthcare Classification Datathon. GradientBoostingClassifier performed best with a mean K-fold cross validation F-1 score of 94.4 %. LowVariance Thresholding feature selection method did any better. 

### Data Description
This dataset contains 1488 records of features extracted from Cardiotocogram exams, which were then classified by three expert obstetritians into 3 classes:

* Normal
* Suspect
* Pathological

Baseline value - Baseline Fetal Heart Rate (FHR)
Accelerations - Number of accelerations per second
Fetal_movement - Number of fetal movements per second
Uterine_contractions - Number of uterine contractions per second
Light_decelerations - Number of LDs per second
Severe_decelerations - Number of SDs per second
Prolongued_decelerations - Number of PDs per second
Abnormal_short_term_variability - Percentage of time with abnormal short term variability
Mean_value_of_short_term_variability - Mean value of short term variability
Percentage_of_time_with_abnormal_long_term_variability - Percentage of time with abnormal long term variability  

### Notes:

* Cross validation is used to observe how model generalizes
* Downsampling is used to solve class imbalance
* GridSearch is used to perform hyper parameter tunning

### Technology Stack 

1. Python  
2. Numpy
3. Pandas
4. Scikit-Learn
5. Matplotlib
6. Seaborn


### How to Run 

- Clone the repository
- Setup Virtual environment
```
$ python3 -m venv env
```
- Activate the virtual environment
```
$ source env/bin/activate
```
- Install dependencies using
```
$ pip install -r requirements.txt
```

### Contributors 

<table>
  <tr>
    <td align="center"><a href="https://github.com/CyrilleMesue"><img src="https://avatars.githubusercontent.com/CyrilleMesue" width="100px;" alt=""/><br /><sub><b>Cyrille M. NJUME</b></sub></a><br /></td>
  </tr>
</table>

### References 

[1] DPhi starter notebook: [https://dphi.tech/notebooks/3649](https://dphi.tech/notebooks/3649)


### Contact

For any feedback or queries, please reach out to [cyrillemesue@gmail.com](mailto:cyrillemesue@gmail.com).
