<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

<div align="center">
    <h2 style="font-size: 44 px;"> Google Play Store Analysis and Prediction </h2><br>
</div>

<div align= "center">
    <img src="https://www.opticflux.com/wp-content/uploads/2021/05/Google-Play-Store.jpg">
</div>

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :writing_hand: HR ANALYTICS
HR analytics is the process of collecting and analyzing Human Resource (HR) data in order to improve an organization’s workforce performance. The process can also be referred to as talent analytics, people analytics, or even workforce analytics. This method of data analysis takes data that is routinely collected by HR and correlates it to HR and organizational objectives. Doing so provides measured evidence of how HR initiatives are contributing to the organization’s goals and strategies.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :round_pushpin: OBJECTIVE

Employee attrition is the rate at which employees leave a company. The goal of this analysis is to model employee attrition and determine the most dominant contributing factors that govern this turnover. Through this kind of analysis, we can understand how many employees are likely to leave, while also determining which employees are at the highest risk and for what reasons.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :innocent: MOTIVATION
The project stems from the potential to improve employee satisfaction, reduce costs, enhance organizational performance, and create a positive workplace culture. It's an opportunity to use data and analytics to make meaningful changes that benefit both employees and the organization as a whole.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :triangular_ruler: SYSTEM ARCHITECTURE

<div align="center"> <img src="https://github.com/shantanu1109/IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction/blob/main/IMAGES/File-5-System-Architecture-Diagram.jpeg" alt="System Architecture"> </div>

#### The methodology for IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction is as follows:-
```
- Load the Dataset: The IBM HR Analytics Attrition Dataset is loaded using the pd.read_csv() function. The head() and info() methods are used to display the first few rows and get information about the dataset, respectively.
- Knowing the Dataset: Basic Information about the dataset is generated; numerical and categorical attributes are enlisted.
- Data Cleaning: Any missing values in the dataset are dropped using the dropna() method.
- Data Visualization: Matplotlib and Seaborn libraries are used to visualize the data. 
- Statistical Analysis: The ANOVA Test is performed to analyze the Numerical Features' Importance in Employee Attrition, while the Chi-Square Test to Analyze the Categorical Feature Importance in Employee Attrition.
- Data Preprocessing: The target variable 'Attrition' is mapped to binary values (1 for 'Yes' and 0 for 'No'). Selected features are extracted from the dataset and one-hot encoded using the get_dummies() function.
- Splitting the Dataset: The dataset is split into training and testing sets using the train_test_split() method from scikit-learn.
- Implementing Machine Learning Algorithms: Logistic Regression, XGBoost, CatBoost, AdaBoost, LightGBM, Decision Tree, and Random Forest classifiers are initialized and trained using the training data.
- Model Evaluation: The accuracy score and confusion matrix are computed to evaluate the performance of each algorithm on the testing data.
- Results: The results, including the accuracy and confusion matrix, are printed for each algorithm.
- Model Performance Comparison: The hvPlot library is used to visualize the ROC curve diagram comparing the performance of all models used.
```

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :file_folder: DATASET
This is a hypothetical dataset created by IBM data scientists. The dataset has (1470R X 35C) that contains numeric and categorical data types describing each employee’s background and characteristics, and labeled with whether they are still in the company or whether they have gone to work somewhere else. 

#### Dataset Attributes
```
01] App
02] Category
03] Rating
04] Reviews
05] Size
06] Installs
07] Type
08] Price
09] Content Rating
10] Genres
11] Last Updated
12] Current Ver
13] Android Ver
```

Dataset Link:
https://www.kaggle.com/datasets/lava18/google-play-store-apps

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :memo: LIBRARIES USED:
```
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Sklearn
- Warnings
```

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :warning: PREREQUISITES

```
- Python Programming
- Data Science
- Data Analysis
- Data Mining
- Data Pre-processing
- Data Visualization
- Statistical Analysis
- Machine Learning Algorithms
- Performance Metrics.
```

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :sparkles: MODEL EVALUATION

#### 2. REGRESSION EVALUATION

| **ALGORITHMS**           | **RMSE (Training)** | **MAE (Training)** | **R2 (Training)** | **RMSE (Testing)** | **MAE (Testing)** | **R2 (Testing)** |
| ----------------------- | ------------------- | ------------------ | ---------------- | ------------------ | ----------------- | --------------- |
| Logistic Regression     | 0.406               | 0.314              | 0.055            | 0.403              | 0.310             | 0.062           |
| K Nearest Neighbor      | 0.343               | 0.262              | 0.328            | 0.422              | 0.321             | -0.026          |
| Random Forest           | 0.405               | 0.314              | 0.063            | 0.402              | 0.310             | 0.068           |

#### 2. CLASSIFICATION EVALUATION

|         ALGORITHMS        | TRAINING  DATA ACCURACY SCORE | TESTING DATA ACCURACY SCORE |
| --------------------------| ----------------------------- | --------------------------- |
| Logistic Regression       |            71.52%             |           71.99%            |
| K Nearest Neighbour       |            80.28%             |           72.39%            |
| Random Forest             |            98.55%             |           72.94%            |

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :key: CONCLUSION
In conclusion, we embarked on a comprehensive analysis of the IBM HR Analytics Attrition Dataset, from data loading to model evaluation. By implementing and evaluating various machine learning algorithms, we gained insights into which models are effective for predicting employee attrition. The results and visualizations generated throughout the process provide valuable information for decision-makers and HR professionals seeking to understand and mitigate employee attrition within the organization. This project showcases the power of data analysis and machine learning in addressing real-world business challenges.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :globe_with_meridians: REFERENCES
```
- 01] Mishra S N, Lama D R and Pal Y 2016 Human Resource Predictive Analytics (HRPA) for HR Management in Organizations International Journal Of Scientific & Technology Research 5(5) 33-35
- 02] Hoffman M and Tadelis S 2018 People Management Skills, Employee Attrition, and Manager Rewards: An Empirical Analysis National Bureau of Economic Research
- 03] Frye A, Boomhower C, Smith M, Vitovsky L and Fabricant S 2018 Employee Attrition: What Makes an Employee Quit? MU Data Science Review 1(1)
- 04] S. Rabiyathul Basariya, Ramyar Rzgar Ahmed, A STUDY ON ATTRITION - TURNOVER INTENTIONS OF EMPLOYEES, International Journal of Civil Engineering and Technology (IJCIET), 2019, 10(1), PP2594-2601
- 05] Halkos, George & Bousinakis, Dimitrios, 2017. "The effect of stress and dissatisfaction on employees during crisis," Economic Analysis and Policy, Elsevier, vol. 55(C), pages 25-34.
- 06] Glavas, A., & Willness, C. (2020). Employee (dis)engagement in corporate social responsibility. In D. Haski-Leventhal, L. Roza, & S. Brammer (Eds.), Employee engagement in corporate social responsibility (pp. 10–27). Sage Publications Ltd. https://doi.org/10.4135/9781529739176.n2
- 07] S. Yadav, A. Jain and D. Singh, "Early Prediction of Employee Attrition using Data Mining Techniques," 2018 IEEE 8th International Advance Computing Conference (IACC), Greater Noida, India, 2018, pp. 349-354, doi: 10.1109/IADCC.2018.8692137.
- 08] R. Jain and A. Nayyar, "Predicting Employee Attrition using XGBoost Machine Learning Approach," 2018 International Conference on System Modeling & Advancement in Research Trends (SMART), Moradabad, India, 2018, pp. 113-120, doi: 10.1109/SYSMART.2018.8746940.
- 09] Alduayj, Sarah & Rajpoot, Kashif. (2018). Predicting Employee Attrition using Machine Learning. 93-98. 10.1109/INNOVATIONS.2018.8605976. 
- 10] Setiawan, Irwan & Suprihanto, Suprihanto & Nugraha, Ade & Hutahaean, Jonner. (2020). HR analytics: Employee attrition analysis using logistic regression. IOP Conference Series: Materials Science and Engineering. 830. 032001. 10.1088/1757-899X/830/3/032001. 
- 11] Yadav, Sandeep & Jain, Aman & Singh, Deepti. (2018). Early Prediction of Employee Attrition using Data Mining Techniques. 349-354. 10.1109/IADCC.2018.8692137.
- 12] I. Ballal, S. Kavathekar, S. Janwe, P. Shete, and N. Bhirud, “People Leaving the Job-An Approach for Prediction Using Machine Learning,” Int. J. Res. Anal. Rev., vol. 7, no. 1, pp. 8–10, 2020, [Online]. Available: www.ijrar.org
- 13] A. Qutub, A. Al-Mehmadi, M. Al-Hssan, R. Aljohani, and H.S. Alghamdi, “Prediction of Employee Attrition Using Machine Learning and Ensemble Methods,” Int. J. Mach. Learn. Comput., vol. 11, no. 2, pp. 110–114, 2021, doi:10.18178/ijmlc.2021.11.2.1022.
- 14] N. Mansor, N. S. Sani, and M. Aliff, “Machine Learning for Predicting Employee Attrition,” Int. J. Adv. Comput. Sci. Appl., vol. 12, no. 11, pp. 435–445, 2021, doi: 10.14569/IJACSA.2021.0121149.
- 15] D. Saisanthiya, V. M. Gayathri, and P. Supraja, “Employee Attrition Prediction Using Machine Learning and Sentiment Analysis,” Int. J. Adv. Trends Comput. Sci. Eng., vol. 9, no. 5, pp. 7550–7557, 2020, doi: 10.30534/ijatcse/2020/91952020.
```

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :scroll: LICENSE
The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
 
<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>
