# upskillcampus
Smart city traffic patterns


## Smart Traffic Forecasting Project

### Overview
Welcome to my Smart Traffic Forecasting project, developed under the internship program with UpSkill Campus and UniConverge Technologies Pvt. Ltd. The goal of this project is to leverage machine learning techniques to forecast traffic patterns in smart city environments, ultimately contributing to more efficient and sustainable transportation systems.

### Internship Experience
This project was undertaken as part of a 6-week internship program facilitated by UpSkill Campus in collaboration with UniConverge Technologies (UCT). Throughout the internship, I received mentorship, practical training, and real-world project experience, empowering me to apply Python programming, machine learning, and data science concepts to solve complex problems. I am immensely grateful to UpSkill Campus and UCT for providing us with this valuable opportunity to enhance my skills and make a meaningful contribution to the field of transportation management.
## Key Features
- Data collection from multiple sources
- Data preprocessing and cleaning
- Analysis techniques for pattern recognition and prediction
- Visualization of traffic patterns and analysis results
- Implementation of findings for real-time monitoring and control
## Data Wrangling
Start by importing necessary libraries and loading the dataset. The dataset includes columns like 'DateTime,' 'Junction,' 'Vehicles,' and 'ID'. Perform data wrangling by:

Converting the 'DateTime' column to a datetime data type.
Creating additional features such as 'Year,' 'Month,' 'Date_no,' 'Hour,' and 'Day.'
## Exploratory Data Analysis (EDA)
Line Plots of Vehicle Count by Time Features and Smart Cities


## Visualizing Average Traffic Patterns by SmartCity
 Analyze the average traffic patterns by grouping the data by junction and time features. Plots are generated for average monthly traffic, traffic by day of the week, traffic by day of the month, and average hourly traffic.

## Count of Traffic in Smart Cities Over the Years
We count and visualize the traffic on junctions over the years to understand how traffic has evolved.

## Correlation Heatmap for Numeric Columns
A correlation heatmap is created to visualize the relationships between numeric columns, including 'Vehicles,' 'Year,' 'Month,' 'Date_no,' and 'Hour.'

## Pairplot of Numeric Columns with Hue by Junction
A pairplot is used to visualize the relationships between numeric columns, with different colors for different junctions.   
## Machine Learning - Traffic Prediction
 Used a Random Forest Regressor to predict the number of vehicles based on various features. This includes one-hot encoding the 'Day' feature and using a grid search to find the best model. Evaluation metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared are used to assess the model's performance.

## Scatter Plot of Actual vs. Predicted Vehicles
Create a scatter plot to compare the actual and predicted values of the number of vehicles, with color differentiation based on prediction values.

## Scatter Plot of Actual vs. Predicted Vehicles (Sample)
A scatter plot of a sample of 100 data points is generated to provide a more detailed view of the model's performance.


## Installation
1. Clone the repository: git clone https://github.com/shirisha0728/upskillcampus.git
2. Install dependencies: pip install
   - python
   - pandas
   - NumPy
   - seaborn
   - matplotlib
   - scikit-learn
   - plotly
## Conclusion
This project provides insights into traffic patterns, allows for traffic prediction, and demonstrates data visualization and machine learning techniques.


## License
This project is licensed under the MIT License.

## Acknowledgements
I would like to thank the open-source community for their contributions and support in developing this project.


