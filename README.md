# Project Proposal

**Authors:** Tanush Vijayakumar Savadi
(tsavadi@umass.edu)
and
Andrew Spiezio
(aspiezio@umass.edu)



## Group Members
Our project group comprises two members: Andrew and Tanush. Andrew will lead the exploratory data analysis, preprocessing, statistical evaluation, and visual interpretation of the results. Tanush will focus on implementing predictive models, including baseline algorithms (Logistic Regression, Linear Regression) and advanced machine learning methods (SVM, XGBoost, Neural Networks). Both members will collaborate closely in interpreting the results, drawing conclusions, and writing the reports throughout the duration of this course/project.

## Motivation
The problem we will investigate in our project is utilizing the Apple Watch/FitBit dataset to detect when an individual is physically active by critically analyzing heart rates (BPM), step counts (SPM), and calories burned (CPM). This is particularly interesting because on these smart devices they periodically prompt the user to "start a workout", or begin tracking BPM/SPM/CPM based on real-time sensor data. However, the criteria involved in prompting such alerts are not always clear. Our goal is to creatively analyze the underlying patterns present in BPM/SPM/CPM to gain a deeper understanding of how these smart devices accurately recognize activity and prompt the user at the right time. Thus, we aim to simplify the way that the decision-making process behind such alerts is communicated to the user and assess if they are accurate and timely in relation to varying activity levels.

## Literature Review
We will conduct literature reviews on prior research covering wearable device data analytics, machine learning applications in activity recognition, and demographic prediction from health metrics. More specifically, we will review recent studies on the reliability of Apple Watch and Fitbit data, as well as literature on advanced statistical methods and machine learning techniques for predictive modeling. One particular one we are closing reading is the research article called Predicting lying, sitting, walking and running using Apple Watch and Fitbit data.

## Data
We will utilize datasets containing metrics from two wearable devices (Apple Watch and Fitbit), capturing variables such as heart rate, steps, distance, calories burned, and demographic information (age, gender, height, and weight) across various activities (lying, sitting, walking, running).

Our initial exploratory analysis (Figures 1-3) shows important differences in heart rate across activities and devices. Figure 1 highlights that running activities have significantly higher average heart rates, especially noticeable with Fitbit data. Figure 2 illustrates that the heart rate distribution varies by device, indicating potential device-specific characteristics. Figure 3 demonstrates a positive correlation between the number of steps and heart rate, with clear clustering of activities, suggesting potential predictability of activities based on these wearable metrics:

1) Average Heart Rate per Activity and Device
2) Heart Rate Distribution by Device
3) Steps vs Heart Rate, colored by Activity

Source: https://www.kaggle.com/datasets/aleespinosa/apple-watch-and-fitbit-data

## Approach
Our approach involves first applying statistical analyses (ANOVA, ANCOVA, correlation analysis, t-tests) to explore significant relationships among heart rate, steps, and physical activities. We will then implement baseline predictive models such as Logistic Regression and Linear Regression to provide initial benchmarks. Following this, more advanced algorithms including Support Vector Machines (SVM), XGBoost, and Neural Networks will be explored. We plan to systematically evaluate and compare these models using metrics such as accuracy, F1-score, and ROC-AUC, along with qualitative visual assessments through plots and figures.

## Evaluation Metric

We will evaluate our results using both qualitative visualizations and quantitative performance metrics.

### Qualitative Analysis (Visualizations)

To explore activity trends and correlations within the dataset, we will generate:

- Heart Rate (BPM) Trends Over Time – Examining how heart rate fluctuates during different activities.
- SPM vs. BPM Scatter Plot – Identifying correlations between step count and heart rate across varying activity levels.
- Activity Classification Accuracy – Visualizing model predictions for low, medium, and high-intensity activities.


### Quantitative Analysis (Statistical \& Model Evaluation)


- ANOVA and t-tests will determine whether heart rate variations across activities are statistically significant.
- Predictive Model Performance will be assessed using accuracy, precision, recall, F1-score, and ROC-AUC to compare baseline and advanced models.
- Device-Specific Comparisons will evaluate consistency between Apple Watch and Fitbit data, identifying potential biases.


