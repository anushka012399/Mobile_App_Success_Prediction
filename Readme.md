# Mobile App Success and Rating Prediction Based On App Features 
A Linear Regression model was built to predict the rating and success of an application based on several factors of an application.<br><br>
***Dataset Description***<br>
The dataset, ‘Google Play Store Apps’ was obtained from Kaggle and used for this
study.<br>
• No of observation (rows): 10840<br>
• Attributes (columns): 13<br><br>
Independent variables:<br>
i. App: This contains the application name<br>
ii. Category: Category of the app<br>
iii. Reviews: No. of user reviews<br>
iv. Size: Size of the app<br>
v. Installs: Number of user installs<br>
vi. Type: Paid or Free<br>
vii. Price: Price of the app<br>
viii. Content Rating: Age group the app is targeted at - Children / Mature 21+ /
Adult<br>
ix. Genres: multiple genres (For eg, a game can belong to Music, Game, Family
genres.<br>
x. Last Updated: Date when the app was last updated<br>
xi. Current Ver: Current version of the app available on Play Store<br>
xii. Android Ver: Min required Android version<br><br>
Dependent variable:<br>
Rating: Overall user rating of the app<br><br>
***Approach Used in the Project***<br>
In this report we would be solving the problem with two methods using, Scikit -learn
and statsmodel.<br>
• We will start by fitting the model using SKLearn. After we fit the model, unlike
with statsmodels, SKLearn does not automatically print the concepts or have
a method like summary. So we have to print the coefficients,intercepts etc.
separately.<br>
• After fitting the model with SKLearn, we fit the model using statsmodels.
Unlike SKLearn, statsmodels doesn’t automatically fit a constant, so you need 
to use the method sm.add_constant(X) in order to add a constant. Adding a
constant, while not necessary, makes your line fit much better.<br>
• Coefficients can be obtained pretty easily from SKLearn, so the main benefit
of statsmodels is the other statistics it provides.<br>
• One of the assumptions of a simple linear regression model is normality of our
data.The statistics in the summary table in statsmodel are testing the
normality of our data.<br>
• If the Prob(Omnibus) is very small, and we took this to mean <.05 as this is
standard statistical practice, then our data is not normal. This is a more
precise way than graphing our data to determine if our data is normal.<br>
Therefore, SKLearn has more useful features, but statsmodels is a good method to
analyze your data before<br><br>
For detailed idea about the project please check the attached pdf "Report Data Science Final" in the repository.
