# nyu_cusp_capstone
Documentation and code for NYU Center for Urban Science + Progress capstone project "Preserving NYC Nightlife Culture Post-COVID-19"

Below are the 6 Main Process Maps that document the code and source files used in this project.
Data pertaining to the LiveXYZ dataset cannot be publicly shared. For access, please request NYC Mayor's Office of Media and Entertainment (MOME) under their Department of Nightlife.

LiveXYZ data (provided by MOME) and Yelp Data (scraped publicly with APIs) were the initial phases of our project. (Refer to **Live XYZ Read Me** and **Yelp Read Me** visualizations)
Through exploratory data analysis, the group was able to glean insight on text analysis to help build neighborhood profiles for the focus regions in NYC.

Sentiment Analysis was used (from Yelp reviews) to determine how positive/negative/neutral patrons felt toward venues in each of the 17 target neighborhoods. (**Refer to Sentiment Analysis Read Me** visualization)

5 Features were then determined to be measured as both a means for displaying neighborhood characteristics as well as their risk likelihood. (Refer to **5 Features Read Me** visualization).
Risk is measured on a relative basis and is a percentage indicating how likely a neighborhood might experience permanent nightlife cultural loss.

These features were calculated in both the Risk Input Model and Neighborhood Profile python notebooks. (Refer to **Dashboard Read Me** visualization)
The visualization shows the inputs into the each of the respective notebooks, and the resulting csv's were used to build interactive dashboards through Tableau as well as inputs for machine learning tools.

A Decision Tree notebook employing regression analysis helped determine which features were most important at influencing risk, while unsupervised learning techniques through Gaussian Mixture Models clustered the neighborhoods to see if any similarities in how neighborhoods behaved. (Refer to Analysis Read Me visualization)

![alt text](https://github.com/[Ruddy-Harnur]/[nyu_cusp_capstone]/blob/[Ani]/https://github.com/nycnightliferesilience/nyu_cusp_capstone/blob/Ani/Live%20XYZ%20Read%20Me.png?raw=true)
