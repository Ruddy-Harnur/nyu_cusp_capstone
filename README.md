# nyu_cusp_capstone
Documentation and code for NYU Center for Urban Science + Progress capstone project "Preserving NYC Nightlife Culture Post-COVID-19"

This Read Me has the 6 Main Process Maps that document the code and source files used in this project.
Data pertaining to the LiveXYZ dataset cannot be publicly shared. For access, please request NYC Mayor's Office of Media and Entertainment (MOME) under their Department of Nightlife.
# 1 <h1> LiveXYZ data (provided by MOME) and Yelp Data (scraped publicly with APIs) were the initial phases of our project. (Refer to **Live XYZ** and **Yelp** visualizations)
Through exploratory data analysis, the group was able to glean insight on text analysis to help build neighborhood profiles for the focus regions in NYC. 


![Live XYZ Read Me](https://user-images.githubusercontent.com/58189651/87869546-880a4900-c955-11ea-8e6f-908da5c7d68d.png)

![Yelp Read Me](https://user-images.githubusercontent.com/58189651/87869610-fd761980-c955-11ea-9790-67d0daea139f.png)
# 2 <h1> 
Sentiment Analysis was used (from Yelp reviews) to determine how positive/negative/neutral patrons felt toward venues in each of the 17 target neighborhoods. (Refer to **Sentiment Analysis** visualization)

![Sentiment Analysis Read Me](https://user-images.githubusercontent.com/58189651/87869621-0ebf2600-c956-11ea-839d-bb0d56fc55b9.png)
# 3 <h1> 
5 Features were then determined to be measured as both a means for displaying neighborhood characteristics as well as their risk likelihood. (Refer to **5 Features** visualization).
Risk is measured on a relative basis and is a percentage indicating how likely a neighborhood might experience permanent nightlife cultural loss.

# 4 <h1> 
![5 Features Read Me](https://user-images.githubusercontent.com/58189651/87869641-2dbdb800-c956-11ea-8fc8-9b55a17319e7.png)

# 5 <h1> 
These features were calculated in both the Risk Input Model and Neighborhood Profile python notebooks. (Refer to **Dashboard** visualization)
The visualization shows the inputs into the each of the respective notebooks, and the resulting csv's were used to build interactive dashboards through Tableau as well as inputs for machine learning tools.

![Dashboard Read Me](https://user-images.githubusercontent.com/58189651/87869645-3a421080-c956-11ea-83d6-6ab243cfe308.png)

# 6 <h1> 
A Decision Tree notebook employing regression analysis helped determine which features were most important at influencing risk, while unsupervised learning techniques through Gaussian Mixture Models clustered the neighborhoods to see if any similarities in how neighborhoods behaved. (Refer to **Analysis** visualization)

![Analysis Read Me](https://user-images.githubusercontent.com/58189651/87869649-4332e200-c956-11ea-945f-7b40cf7c71f1.png)
