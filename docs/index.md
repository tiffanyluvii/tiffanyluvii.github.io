# **An Analysis of the Different Factors that Affect The Priority Level a 911 Call is Classified As.**

###### Fall 2024 Data Science Project
###### Collaborators: Ryan Eldho, Tiffany Lu, Akshay Badrinathan, Eli Choi

<h2 style="text-align:center;">Introduction</h2>

In this tutorial, we will walk through the entire Data Science Life Cycle. To illustrate this process, we will focus on how various factors influence the priority of 911 calls in Baltimore. These factors include the district where the crime occurred, the type of crime, and the time of the incident. As you may know, Baltimore is often ranked among the top ten most dangerous cities in the United States. There is a lot of useful and interesting information such as the types of calls coming from different regions, the dates during which the crimes happen, and how the police system prioritizes different crimes. We can use this information to inform potential residents like ourselves as to what regions have higher and lower rates of serious crimes, and the police system can use this information to distribute their resources accordingly. Furthermore, the conclusions we gather from this dataset can help assist the police systems in how to prepare for crimes in certain districts and the number of officers that should be on duty at a certain time.

Identifying patterns that directly correlate with high-priority calls could help reduce crime in the city and ultimately improve its safety, potentially removing it from the list of dangerous cities. This is why we chose to use Data Science to identify the key factors behind high-priority calls. This analysis could drive policy changes that make Baltimore a safer community. For instance, discovering that a particular district experiences a higher frequency of high-priority calls than others could result in the allocation of more police resources to that district. Similarly, if a specific crime is more prevalent in Baltimore compared to other cities, targeted policies could be introduced to reduce that crime. Not only would this enhance the quality of life in Baltimore, but it would also lead to more efficient use of existing resources.

<h6 style="text-align:left;">Contents</h6>
1. <a href="#datacollection">Data Collection</a>
2. <a href="#dataprocessing">Data Processing</a> 
3. <a href="#explore">Exploratory Analysis and Data Visualization</a>
4. <a href="#ml">Analysis, Hypothesis Testing, and ML</a>
5. <a href="#insights">Insights and Conclusions</a>

<div id = "datacollection">
<h2 style="text-align:center;">Data Collection</h2>

The Data Collection Stage of the Data Science Life Cycle consists of finding relevant information that assists us in our analysis of 911 calls in Baltimore. One main criterion that we wanted to have in our dataset was plenty of entry points. This would allow us to easily determine any correlation that a factor has on the 911 call with more precision.

Luckily the Baltimore 911 Dataset from Kaggle has over 200 thousand 911 calls from 2015 onward. Each call input has details including date, call time, district, district, description, etc. This gives us plenty of information to explore.

After clicking on the [Kaggle Dataset](https://www.kaggle.com/datasets/sohier/baltimore-911-calls), download the following dataset. It should show up as 911_calls_for_services.csv in your Downloads folder. Remember to move it to your project directory!

Besides the dataset, we also need an IDE to develop this project in. We decided to code in Python as there are already plenty of libraries that we can utilize to help us throughout this Data Science Life Cycle. We also decided to work with [Jupyter Notebook](https://www.codecademy.com/article/introducing-jupyter-notebook#:~:text=Jupyter%20Notebook%20is%20a%20type,%2C%20debugging%2C%20and%20code%20completion.) as you're able to easily write Python code with it. 

Before we start utilizing the libraries, we must import them within the Jupyter Notebook. Some common libraries that we will be utilizing are [Pandas](https://pandas.pydata.org/docs/user_guide/index.html), [NumPy](https://numpy.org/doc/stable/user/), [SeaBorn](https://seaborn.pydata.org/tutorial/introduction.html), and [PyPlot](https://matplotlib.org/3.5.3/api/_as_gen/matplotlib.pyplot.html).

##### Reasons Why We Use Each Library

Pandas is a powerful Python library for data manipulation and analysis, offering flexible data structures like DataFrames and Series to efficiently handle, clean, and transform data. It supports various operations such as filtering, grouping, aggregation, and handling missing values, making it essential for tasks like data cleaning, exploration, and time series analysis.

NumPy is a fundamental Python library for numerical computing, providing efficient array objects and a wide range of mathematical functions for operations on large datasets. 

Seaborn is a Python visualization library that simplifies the process of generating complex plots like heatmaps, boxplots, and line plots while integrating well with Pandas data structures. Seaborn is widely used for data exploration and visualizing relationships in datasets, especially in statistical analysis.

Pyplot is a module in Matplotlib that also offers functions to generate basic charts for visualization like line plots, bar charts, histograms, and scatter plots. Pyplot is used for its flexibility in creating custom plots for data analysis.


Below are the imports that you must have before we continue with **Data Processing**!

</div>

<div id = "dataprocessing">
<h2 style="text-align:center;">Data Processing</h2>
</div>

<div id = "explore">
<h2 style="text-align:center;">Exploratory Analysis and Data Visualization</h2>
</div>

<div id = "ml">
<h2 style="text-align:center;">Analysis, Hypothesis Testing, and ML</h2>
</div>

<div id = "insights">
<h2 style="text-align:center;">Insights and Conclusions</h2>
</div>
