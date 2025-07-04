# Medical_Expensece_for_Customers

In this video, you will work on a Machine Learning Predictive Analysis Project.

To set up the Environment.

You will need to Install Python Version 3.6.8 and then also Install Jupyter Notebook on your System as you are going to work on this Project using Jupyter Notebook.

If you have not Installed Python and Jupyter Notebook, go to Python Fundamentals Course Section 1 Lesson 2 where you will get to know how to Install Python and Jupyter Notebook.

As, you have already Installed Jupyter Notebook in your System, Open it in Chrome Browser.

Click on the New Button and then Click on Folder to make a New Folder, Name the Folder “Health Expenses of Customers”.

Go Inside the Folder, and Click on Upload Button to upload the dataset used for this Project, download the Dataset from the Resources Section of this Project Course.

After Uploading the Dataset in this Folder, Create a New Jupyter Notebook, Where you will write the code for the Project.

Open this Jupyter Notebook and Change the Name of this Notebook to “Health Expenses of Customers”.

In this Project, you require some Python Libraries, which needs to be Installed and Imported.

To Install these Libraries, you just have to Open your Command Prompt and type “pip install name of library”.

Using Python Libraries: -

Numpy for Mathematical Calculations.
Pandas for Dataframe Manipulations.
Seaborn, Matplotlib and plotly for Data Visualizations.
Plotly is an advanced Data Visualization Library which will helps to Build amazing and Interesting Visualizations for driving huge Business Insights.
And at last set the Figure Size and Background for your Visualizations.
In this case, you are going to set the Figure size as 16 units for x axis, and 5 units for y axis.

You are selecting the “Fivethirtyeight” Background for our Plots, If you wish to select any other Background for your Charts then you can just type the command: “plt.style.available” and pick up any of the Styles for your Charts.

In the next video, you are going to understand the Features present in the Dataset in Details.


________________________________________________________________________________________________________________________________________________

In this video, you are going to take a deep dive into the dataset and try to understand the significance of all the columns present in the dataset for predicting the medical expenses.

To import the dataset into the jupyter notebook using read_csv() function of pandas library.

As the data is imported, check the shape of the dataset.

After Executing the Program, an output is (1338, 7). Means the dataset contains 1338 rows and 7 columns.

Look at the columns of the dataset.

The columns present in the dataset are ‘age’, ‘sex’, ‘bmi’, ‘children’, ‘smoker’, ‘region’ and ‘expenses’.


You Might have already understood that the “Expenses” column is the target column and the rest others are independent columns.

Independent Columns are those columns using which you will predict the Target Column.

Try to answer which of the independent columns present in the dataset are important to predict the medical expenses.

You will be using your Instincts to Judge whether a Column can be Important or Not Important for Predicting the Medical Expenses of a Patient.

The first column is Age. Age is an important factor for predicting medical expenses, because the young people are generally more healthy than old ones.

And the Medical Expenses for the Young People will be quite less as compared to Old People.

The Next column is sex, you have two Categories in this column: Male and Female. The Sex of the person can also play a vital role for predicting the medical expenses of a Patient.

So, concluding that this Column is also an Important factor to predict Medical Expenses.

After that, you have the ‘bmi’ column, then BMI is Body Mass Index.

For most adults, an ideal BMI is in the 18.5 to 24.9 range.

For children and young people aged 2 to 18, the BMI calculation takes into account age and gender as well as height and weight. If your BMI is: below 18.5 – you are in the underweight range.

Now you must have got some clarity about What BMI is and How it can be useful for estimating the Medical Expenses for the Patients.

As the people having very less bmi or very high bmi have more chances of needing medical help and hence more expenses.

Now you have the ‘children’ column, this column gives information about the Number of Children's your Patients have.

The People who have Children's have more pressure due to the Education, and Other Requirements of their children's as compared to the People who do not have Children's.

This column is also an Important factor to determine the Medical Expenses of our Patients.

After that, you have the ‘smoker’ column. The Smoking factor is also considered to be one of the Most Important factors as the people who smoke are always at risk when their age reaches 50 to 60.

You have the ‘region’ column, you need some more information about the Different Regions specified in the Dataset.

Some Regions are Hygienic, Clean, Neat and Prosperous, But some Regions are not, and these information's are not revealed about the Regions. So, you must not consider anything about this particular factor. You will come to know about the Usefulness of this factor only and only after analyzing and comparing this column with respect to the “Expenses” Column.

In the next video, you are going to understand the problem statement of this Project.

________________________________________________________________________________________________________________________________________________

In this video, you are going to understand the problem statement of this project. You are going to Predict the Future Medical Expenses of our Patients using some of the relevant information that is provided in the dataset. Also discussed about the Factors and their Importance's in determining the Medical Expenses of our Patients based on certain features. Such as the Age, The Gender, The Body Mass Index, The Region, The Smoking Behavior. You know that the Medical Expenses will be a Numerical and Continuous Value. Hence, this Predictive Analysis is going to be a Regression Problem. To Solve the Problem, using a lot of Regressors such as Linear Regressor, Random Forest Regressor etc. Also understanding the Business Implications of this Project, and How this Project can be helpful in terms of Money Making or Money Saving. As the craze of Fitness is growing, you can rightly say that everyone wants to stay fit and strong. Whenever you open our Instagram or Tiktok, you can find thousands of people endorsing Fitness and educating that how Fitness is so Important. Every part of your life relies on having good health. You cannot climb in all the areas of your life if we do not have enough physical energy to devote.
Health is basically the extent of an individual’s continuing physical, emotional, mental and social ability to cope with the environment.
And just because of that you spend a lot of money just to stay fit. You can Make an application which can helps people to understand the factors which are making them unfit and the factors which are making them unfit so that it can reduce their Medical Expenses. Or else you can use this Health Expense Predictor in Hospitals so that the Patients can adjust their Medical Expenses. In the next video, you will perform Univariate Analysis, and understand the distribution of the factors in the dataset.
________________________________________________________________________________________________________________________________________________

In this video, you are going to perform Univariate Analysis in the data and find some interesting facts about the features in the dataset.
Univariate analysis is perhaps the simplest form of statistical analysis. Like other forms of statistics, it can be inferential or descriptive.
The key fact is that only one variable is involved. Univariate analysis can sometimes yield misleading results in cases in which multivariate analysis is more appropriate.
But Still Univariate Analysis is considered to be one of the Most Essential steps in any Data Science or Machine Learning Project. Use the Distribution plots provided by seaborn library to check the distribution of Numerical Columns present in the Dataset. Also check the distribution for Categorical Columns using Pie charts, and Count plots again provided by the seaborn library. Generally use the Pie charts when you have very few categories in the categorical column. Whereas you use the count plots in cases where you have more number of categories in the categorical column present in the dataset. Now, as you have so much knowledge on performing univariate analysis. You will use a pie chart to plot the Smoker Column, as the Smoker column has only two values: Yes and No. Where “Yes”, means the patient is smoker, and “No” means that the patient is a non-smoker. You will see that only around 25% of the patients are smokers, rest of the patients are non-smokers. After that for plotting the Number of Children's Columns: - Using a Count plot, as the Children's Column can have values ranging from 0 to 5. Where 0 means that the Patient is not having any children, and 1 means the patient is having one child and so on. Now, you can see that Most of the patients do not have any child, and very few parents have 4 or 5 children. And for the Region column, you are again going to use the pie chart, As The Region column consists only of 4 values: Southeast, southwest, northeast, northwest. And It is clearly visible that all the 4 regions are having equal numbers of habitants. We have plotted all these three plots together using the subplots function in matplotlib library. Also, you have used various colors to make it look beautiful!!! Making Beautiful Charts is very important, so that the people can spend some more time finding insights on it. Check the distribution of Age, BMI and Expenses using the distribution plot provided by the seaborn Library. After taking a look at the distribution plotted by the distplot. You can say that you have an equal number of people of all ages. The BMI of the patients seems to be normally distributed where maximum people have bmi around 30. And very few people have less BMI around 10, similarly very few people have high BMI around 60. And Finally the Expenses column seems to be right skewed. Now, If you don’t understand what is skewness and How it can be a severe Problem. Pause this video and go to the Statistics and Probability Course, Learn about the Concept of Skewness and how to deal with it. As the Expenses Column is skewed in Nature, You can either transform this Column using log transformation or square root transformation and convert it into a Normal Distribution. Or else, you can leave it as it is and check the Results. If the Results are too poor, then In that case, you have to transform the Expenses Column using Log or Square root transformation. And If the Results are good, then leave it as it is. Looking at the Expenses column, You can see that most of the patients have Expenses around 5000 to 20,000 Whereas there are very few people who have expenses greater than 40,000. You can also study those Patients carefully, who have Very High Medical Expenses. And Try to understand the Factors which are affecting them so that to come up with better precautions for our patients. In the next video, you we will perform Bivariate Analysis. Bivariate Analysis is a Part of Data Visualization where we try to visualize the Impact of one variable on the other.
