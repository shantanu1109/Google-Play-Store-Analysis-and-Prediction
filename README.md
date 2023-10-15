<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

<div align="center">
    <h2 style="font-size: 44 px;"> Google Play Store Analysis and Prediction </h2><br>
</div>

<div align= "center">
    <img src="https://www.opticflux.com/wp-content/uploads/2021/05/Google-Play-Store.jpg">
</div>

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :writing_hand: GOOGLE PLAY STORE
Google Play Store is a digital distribution platform developed and operated by Google. It serves as the official app store for Android operating systems, offering a wide range of applications, games, movies, music, and other digital content that users can download and install on their Android devices, such as smartphones, tablets, and smart TVs. The platform provides a convenient and secure way for Android users to discover, purchase, and download a diverse array of software and media content. It also includes user reviews, ratings, and recommendations to help users find high-quality apps and content.

Developers can publish their Android applications on the Google Play Store, making them accessible to a global audience of Android users. Users can browse and search for apps and other digital content, and many apps are available for free, while others require a purchase or offer in-app purchases. Google Play Store also provides updates for installed apps, ensuring that users have access to the latest features and security patches.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :round_pushpin: OBJECTIVE

The objective of this project was to perform a comprehensive analysis of the Google Play Store, addressing various problem statements to gain insights into app categories, ratings, content ratings, sentiments, genres, pricing, size, and correlations between different variables. By analyzing these aspects, the project aimed to provide valuable insights for app developers and stakeholders to make informed decisions in the highly competitive app marketplace.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :innocent: MOTIVATION
Although the success rate of apps is on the decline, the annual growth rate of apps continues to increase. Retaining users over an extended period is becoming increasingly challenging for developers who fail to focus on crucial factors. Numerous aspects that developers might overlook during the app's development can lead to its failure. Consequently, we are examining a handful of essential elements and presenting them to developers to assist in their application development efforts.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :triangular_ruler: SYSTEM ARCHITECTURE

<div align="center"> <img src="https://github.com/shantanu1109/Google-Play-Store-Analysis-and-Prediction/blob/main/IMAGES/File-6-System-Architecture-Diagram.jpeg" alt="System Architecture"> </div>

#### The methodology for Google Play Store Analysis and Prediction is as follows:-
```
- Knowing the Dataset: The dataset containing Google Play Store Apps information has been imported into a data frame to extract fundamental details about its attributes and produce statistical summaries for the numerical columns.
- Data Cleaning: We examined the dataset for any missing values, and to address this issue, we implemented three different techniques: removing rows with missing data, imputing missing values with either the mean or median, and employing random sample imputation. We opted for the random sample imputation method to clean the data because it did not affect the distribution pattern.
- Data Visualization: Matplotlib, Seaborn, and Plotly are employed for data visualization purposes, and we conducted a comprehensive analysis of the Google Play Store dataset to gain insights and understand its descriptive statistics.
- Statistical Analysis: We performed hypothesis testing to assess the normality of the data. We utilized the Shapiro-Wilk test, K^2 normality test, and Q-Q plots to evaluate the distribution, and it was evident that the variable did not conform to a normal distribution. Consequently, we applied various transformations like logarithm, square root, and Yeo-Johnson techniques, among which the Yeo-Johnson transformation yielded satisfactory results.
- Outlier Detection: We employed a range of methods to identify outliers within the dataset. These techniques included the Z-Score, the Interquartile Range Method (IQR), and comparing the skewness of data. These approaches were utilized to detect and flag data points that deviated significantly from the norm.
- Data Preprocessing: The 'Rating' variable of interest was isolated, and we also identified and extracted the specific features from the dataset that we deemed essential. This prepared dataset is now in a state where it can be readily divided for further processing during data splitting.
- Splitting the Dataset: We divided the dataset into two distinct sets: a training set and a testing set. This partitioning process was achieved by utilizing the 'train_test_split()' method provided by the scikit-learn library.
- Implementing Machine Learning Algorithms: - In this data modeling project, we employ a combination of algorithms, including Linear Regression, K-nearest neighbors (KNN), and Random Forest. These algorithms are utilized to handle both classification and regression tasks within the project.
- Model Evaluation: In the context of regression models, we assess the algorithms' performance by measuring metrics like Root Mean Square Error (RMSE), Mean Absolute Error (MAE), and R-squared (R2). Meanwhile, for classification tasks, we rely on a single metric, which is accuracy.
```

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :file_folder: DATASET
This dataset comprises information from 10,000 Play Store apps, which have been scraped from the web and are accessible on Kaggle. This data presents a valuable opportunity to analyze the Android market, providing valuable insights that can be harnessed by app developers to enhance their chances of success.

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

#### 1. REGRESSION EVALUATION

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
To summarize, we conducted an exploration and analysis of the dataset sourced from Google Play Store apps, employing various data visualization techniques facilitated by libraries like Matplotlib and Seaborn.
Our initial examination, utilization of visualization tools, and exploratory data analysis (EDA) provided valuable insights into the dataset, enhancing our comprehension of inherent patterns and associations among the different variables.
Our scrutiny of the Google Play Store dataset revealed a limited correlation between app ratings and other attributes like app size, number of installations, user reviews, and pricing. Notably, we identified a moderately positive correlation between the number of installations and app ratings, indicating that apps with higher ratings tend to accumulate more installations.
Furthermore, our observations indicated that free apps tend to receive higher ratings compared to their paid counterparts, and the size of the app does not appear to significantly influence the app's rating.

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :globe_with_meridians: REFERENCES
```
- 01] Statista, Number of available applications in the Google Play store from December 2009 to March 2019, https://www.statista.com/ statistics/266210/numberof-available-applications-in-the-google-play-store/, Online: accessed 22 May 2019.
- 02] Statista, Number of mobile app downloads worldwide in 2017, 2018 and 2020 (in billions), https://www.statista.com/statistics/271644/worldwide-free-and-paid-mobile-app-storedownloads/, Online: accessed 22 May 2019.
- 03] R. M. Amir Latif, M. Talha Abdullah, S. U. Aslam Shah, M. Farhan, F. Ijaz, and A. Karim, "Data Scraping from Google Play Store and Visualization of its Content for Analytics," 2019 2nd International Conference on Computing, Mathematics and Engineering Technologies(iCoMET), Sukkur, Pakistan, 2019, pp. 1-8.
- 04] Rimsha Maredia, “Analysis of Google Play Store Data set and predict the popularity of an app on Google Play Store”, Texas A&M University College Station, Texas, June 2020.
- 05] T. Chumwatana, Using sentiment analysis technique for analyzing Thai customer satisfaction from social media, 2015.
- 06] Maredia, Rimsha. (2020). Analysis of Google Play Store Data set and predict the popularity of an app on Google Play Store. 
- 07] H. Hanyang et al., Studying the consistency of star ratings and reviews of popular free hybrid android and ios apps, Empirical Softw. Eng. 24 (2019), no. 7, 7–32.
- 08] Aralikatte, R., Sridhara, G., Gantayat, N., and Mani, S. (2018). Fault in your stars: an analysis of android app reviews. In Proceedings of the ACM India Joint International Conference on Data Science and Management of Data, pp. 57–66. ACM. 
- 09] F. Hurley, Android Developers Blog: Android Vitals: Increase engagement and installs through improved app performance, 10-Jul-2017. [Online]. Available: https://android-developers.googleblog.com/ 2017/07/android-vitals-increase-engagement-and.html. [Accessed: 12-Feb-2019].
- 10] M. Nayebi, H. Farahi, and G. Ruhe, Which Version Should Be Released to App Store?, in 2017 ACM/IEEE International Symposium on Empirical Software Engineering and Measurement (ESEM), Toronto, ON, 2017, pp. 324333.
- 11] Chin-Lung Hsu and Judy Chuan-Chuan Lin. 2015. What drives purchase intention for paid mobile apps? - An expectation confirmation model with perceived value. Electron. Commer. Rec. Appl. 14, 1 (January 2015), 46–57.  
- 12] Akhlak Ali Sunasara, Nancy Jaiswal, Suchit Poojari, Anil Kumar Chaturvedi, (2021) "Play Store App Analysis", International Research Journal of Engineering and Technology (IRJET), pp. 3888-3893.
- 13] Cuiyun Gao, Jichuan Zeng, Michael R. Lyu, and Irwin King, “Online App Review Analysis for Identifying Emerging Issues”, ACM/IEEE 40th International Conference on Software Engineering, Shenzhen Research Institute of The Chinese University of Hong Kong, China 2018.
- 14] Liu Yezheng, Du Fei, Jiang Yuanchun, Liu Xiao, Wang Qiudan, “A Novel APPs Recommendation Algorithm Based on APPs Popularity and User Behaviors”, IEEE First International Conference on Data Science in Cyberspace, China, Australia-2016.
- 15] M. Harman, A. Al-Subaihin, Y. Jia,W. Martin, F. Sarro, Y. Zhang, “Mobile App and App Store Analysis, Testing, and Optimisation”, IEEE/ACM International Conference on Mobile Software Engineering and Systems, University College London, CREST Centre UCLappA Group, London, WC1E 6BT, UK-2016.
```

<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>

### :scroll: LICENSE
The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
 
<a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>
