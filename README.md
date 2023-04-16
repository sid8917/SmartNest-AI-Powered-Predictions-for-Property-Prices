
# SmartNest-AI-Powered-Predictions-for-Property-Prices


SmartNest is a machine learning project that predicts the housing prices of a given area using linear regression algorithms. It uses large datasets and cutting-edge techniques to provide accurate and reliable pricing information and market insights, making it easier for buyers, sellers, and real estate agents to make informed decisions.



The steps followed for the project were:



<h1>1) Model Building</h1>



* Data Load: Load banglore home prices into a dataframe

* Data Cleaning: Handle NA values

* Feature Engineering

* Dimensionality Reduction

* Outlier Removal Using Business Logic

* Outlier Removal Using Standard Deviation and Mean
<h2>Outlier Removal in Rajaji Nagar</h2>
<p float="left">
  <img src="https://user-images.githubusercontent.com/102037657/232305587-675c1739-3792-4f78-a67c-0bdd079876b5.png" width="400"/>
  <img src="https://user-images.githubusercontent.com/102037657/232305604-f6eba713-4370-4899-8855-64f19f0e417d.png" width="400"/>
</p>

<h2>Outlier Removal in Kanakpura Road</h2>
<p float="left">
<img src="https://user-images.githubusercontent.com/102037657/232305605-ee4155fc-bed5-4277-981f-7d7d30113652.png" width="400"/>
<img src="https://user-images.githubusercontent.com/102037657/232305629-62763377-ba2e-4e2b-863a-44f2e4a4fe13.png" width="400"/>
</p>

* Used One Hot Encoding For Location

* Built a Model

* Used K Fold cross validation to measure accuracy of our LinearRegression model

* Found best model using GridSearchCV

* Evaluated and Exported the tested model to a pickle file
<h2> Evaluation</h2>
We can see that in 5 iterations we get a score above 80% all the time. This is pretty good but we want to test few other algorithms for regression to see if we can get even better score. We will use GridSearchCV for this purpose.
Based on above results we can say that LinearRegression gives the best score. Hence we used that.
<img width="960" alt="2023-04-16 (8)" src="https://user-images.githubusercontent.com/102037657/232309097-aca6cc60-bece-4187-840b-4fa5c00b3a7d.png">



<h1>2)Built a website using html,css,javascript and used flask for backend, deployed it on Amazon AWS EC2.</h1>
<img width="960" alt="2023-04-08" src="https://user-images.githubusercontent.com/102037657/232303289-c0e4e2cb-9a79-45bd-8112-b3c0fbc064a0.png">
<img width="960" alt="2023-04-08 (1)" src="https://user-images.githubusercontent.com/102037657/232302966-ac5d676d-9aaf-4136-abb4-407a1202fe1c.png">

