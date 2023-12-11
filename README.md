# Data-Analytics
## Statistics for Data Scientist
Data science includes extracting data and results, and statistics focus on the analysis and communication of the data results. Statistical data science works to explain the trends and results of a data set by identifying the statistical correlations and distribution of variables and values.

### Probability
The probability is the measure of the likelihood of an event to happen. It measures the certainty of the event. The formula for probability is given by; P(E) = Number of Favourable Outcomes/Number of total outcomes.

Example of probability :

First we need to have a number of favourable outcomes or as known as n(A). Here we will calculate what percentage chance a male passenger has of surviving from all the ship's passengers

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/1bdec9fc-cf54-404f-8825-f62f5b26f919)

After that wee need  total number of events in the sample space or n(S).

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/214f5f5d-9b15-4604-b24c-41ef1ef626ec)

Then, We have to enter the values we got earlier into the probability formula = P(A) = n(A)/n(S)

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/727502e6-1b62-476b-b5c7-f200aead5be4)

### Measure of central tendency
The central tendency measure is defined as the number used to represent the center or middle of a set of data values. The three commonly used measures of central tendency are the mean, median, and mode.

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/aa59890e-00fc-469e-be3c-198b781c5ae9)

### Range
Range, which is the difference between the largest and smallest value in the data set, describes how well the central tendency represents the data.

Example of range :

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/9f3e5053-60d6-49bc-a900-ea570a199853)

### Variance
The term variance refers to a statistical measurement of the spread between numbers in a data set. More specifically, variance measures how far each number in the set is from the mean (average), and thus from every other number in the set.

Example of variance :

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/86a24499-099d-4bbd-8cb5-83a8382a72ae)

### Standard Deviation
A standard deviation is a measure of how dispersed the data is in relation to the mean. Low, or small, standard deviation indicates data are clustered tightly around the mean, and high, or large, standard deviation indicates data are more spread out.

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/9c4fef0e-1e60-4b58-ada1-bb09f3a4bf4f)

### Quantile
Quantiles are values that split sorted data or a probability distribution into equal parts.

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/997ba66a-ee47-4e54-b12d-f3f3a7f42824)

## Hypothesis Testing
Hypothesis testing is a systematic procedure for deciding whether the results of a research study support a particular theory which applies to a population. Hypothesis testing uses sample data to evaluate a hypothesis about a population.

Libraries that are needed in hypothesis testing

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/2c4f41e6-4898-4b70-b88d-9e016057c057)

In hypothesis testing there are t-test and p values. A t test is a statistical test that is used to compare the means of two groups. The P value is defined as the probability under the assumption of no effect or no difference (null hypothesis), of obtaining a result equal to or more extreme than what was actually observed.

Example of hypothesis testing :

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/91644500-32ec-4e98-868c-2bdac9c37e2a)

## Simple Linear Regression
Simple linear regression is a regression model that estimates the relationship between one independent variable and one dependent variable using a straight line. Both variables should be quantitative.

For example, here we’re gonna do a simple linear regression using height-weight dataset :

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/a51dbc5d-65fb-4c46-b55f-94df8b92f2ed)

Here we create two variables x and y, then we have to separate the train set and test set using train size 1/3 and random state 42.

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/862fadd7-f968-42f0-84d6-ee9bf441c6fb)

Here we store the LinearRegression into variable named regressor and fitting it into training. We also can see the coefficients.

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/1ca73492-9e66-4ed5-9649-4fc0ad0ab1d1)

After that, we’re going to predict the result, y_pred is a variable that will store the output and X_test is the predictor. And then we create a variable called result which contains the actual values and the predict values.

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/beb7fc97-b18a-46a3-b580-f6fbbf374675)

Scatter plot output :

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/01aae05e-ce99-472c-8dbe-136ac21dbfa6)

Here we can see the MSE, MAE, MAPE, and r2 values. The r2 value is 0.98 or 98%, if the r2 value is closer to 1 or 100%, the more accurate the forecasting results are

![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/5ea84504-58f2-4d1e-8438-7ead44c84664)

# Data Visualization
The process of finding trends and correlations in our data by representing it pictorially is called Data Visualization. To perform data visualization in python, we can use various python data visualization modules such as Matplotlib, Seaborn, Plotly, etc. here we're going to use matplotlib and seaborn. Matplotlib is a cross-platform, data visualization and graphical plotting library (histograms, scatter plots, bar charts, etc) for Python and its numerical extension NumPy. Matplotlib is powerful tool for executing a variety of tasks. It is able to create different types of visualization reports like line plots, scatter plots, histograms, bar charts, pie charts, box plots, and many more different plots. Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

- Line chart
  
  A line chart is a type of chart used to show information that changes over time. Line charts are created by plotting a series of several points and connecting them with a straight line. Here is an example how to create a line chart using matplotlib with darkgrid seaborn style.

  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/8622c9b8-9ac2-4bb7-b083-699cdd44ddad)

  Output :<br>
  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/354bddec-5e52-45b3-a0ab-81c5c49feef9)

- Bar graph using matplotlib
  
  A bar graph is a graphical representation of information. It uses bars that extend to different heights to depict value. Here is how to make a bar graph using matplotlib :
  
  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/022dc68c-6677-4723-b2a2-a5e92a91f4b3)

  utput :<br>
  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/c5fe7751-d98a-48da-9a7c-dc48f84a6b84)

- Stacked bar graph using matplotlib

  A stacked bar chart, also known as a stacked bar graph, is a graph that is used to break down and compare parts of a whole. Each bar in the chart represents a whole, and segments in the bar represent different parts or categories of that whole. Here is how to create a stacked bar graph.

  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/b8f6ae04-23d3-4185-b22d-94875f250e4e)

  Output :<br>
  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/de60ae60-f66d-4813-94bc-5b6221d75bbf)

- Bar chart using seaborn

  A bar graph can also be created using seaborn. Here is how to make a bar graph using seaborn :

  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/d8516fe9-6c72-4100-b280-4066cd97ecef)

  Output :<br>
  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/c7a98a9c-9b82-4464-868b-b47d0ee70a97)

- Multiple histograms in a single chart

  Similar to line chart, we can draw multiple histograms in a single chart. lets drew separate histograms for each species

  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/f178bd3d-8a57-4ed0-a4f2-06e88d35e1f0)

  Output :

  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/8d581d6c-fe4c-4965-9b5c-6d75170b5bd8)

- Multiple stacked histograms

  Multiple histograms can be stacked on top of one another by setting the stacked parameter to True.

  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/075b5261-a767-4520-baf2-d2bc8bc57c4c)

  Output :

  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/2795ecc7-3ba5-4612-a8fc-e393ca55644d)

- Stacked histogram using seaborn

  Stacked histogram can also be created using seaborn. here's how to make a stacked histogram using seaborn :

  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/6903413b-d9ff-4751-a352-9d5506b52ea9)

  Output :

  ![image](https://github.com/vinamaulina/Data-Analytics/assets/114405502/31d30c57-22a8-4af0-8e39-df31e1e70b45)
