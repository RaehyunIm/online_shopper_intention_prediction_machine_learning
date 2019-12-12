# Dataset Information:

The dataset consists of feature vectors belonging to 12,330 sessions to a e-commerce webpage. The dataset was formed by each session or visit belong to different users for a 1 year period of time to sssion would belong to avoid any tendency to a specific campaign, special day, user profile, or period.
The dataset composes of 20 features and 1 response, the revenue of which boolean value indicates whether a session or a visit was ended with purchase or not. 

# Objective
In this project, we are set to use given infomration to streamline classification machine learning models in order to predict the binary outcome of the target variable.
we will clean and manipulate data, explore data through readerable visualization to capture interesting trend and pattern.
Analyze features' relationship with the target using classification machine learning algorithms, and enhance its capacity to predict binary outcome customer behavior in binary term

# Feature Information:
The dataset consists of 10 numerical and 8 categorical features. The 'Revenue' feature can be used as the class label.

**Features**:

"Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories.
The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action.
"Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site.
The value of "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session.
The value of "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session.
The"Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction. 
"Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction.
The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. 
The dataset also includes "Opearating Systems", "Browser", "Region", "Traffic Type", "Visitor Type" as returning or new visitor, 
Boolean value indicating whether the date of the visit is "weekend", "month" of the year, and finally the target variable, "Revenue"

# Workflow stages:
The competition solution workflow goes through seven stages, generally used in Data Science
1. Question or problem definition.
2. Acquire and load data
3. Prepare, cleanse the data.
4. Analyze, identify patterns, and explore the data using visualization
5. Model, predict and solve the problem.
6. Visualize and report the score of predictions of each models
7. Model Evaluation

# Library
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit Learn
- Axes3D
