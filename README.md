# <font color="blue"><u>Introduction:</u></font>

In this project, we are exploring the concept of "star" ratings for Marriott Hotels, specifically analyzing the factors that contribute to a hotel earning 2, 3, 4, or 5 stars. The goal is to understand what makes a hotel stand out as a "star" hotel and, based on the findings, recommend strategies to improve the standards of Marriott’s lower-rated hotels, particularly those with 2-3 stars. By analyzing hotel features such as amenities, services, and facilities, we aim to provide actionable insights that can help elevate the brand's overall standing, especially in smaller cities and airports where Marriott’s hotels tend to have lower ratings.

# <font color="green"><u>Overview:</u></font>

For this analysis, we leveraged a database containing data on various hotels across the United States, with a focus on Marriott hotels. The dataset includes features such as location, amenities, staff services, and facilities, along with customer ratings and star classifications (ranging from 1 star to 5 stars).


The analysis aims to answer the following key questions:
- What key features differentiate a 2-star hotel from a 5-star hotel in the Marriott chain?
- Which amenities, services, and facilities most strongly influence a hotel’s rating?
- Can we identify the specific changes that could help elevate the quality of Marriott’s lower-star hotels?

# <font color="red"><u>Business Understanding:</u></font>

The primary goal of this project is to identify which factors drive a hotel’s rating within the Marriott chain, and specifically how Marriott can improve the standards of its 2-3 star hotels to make them more competitive with higher-rated properties. Key objectives include:
1. **Feature Identification:** What amenities, services, and facilities most impact a hotel’s rating?
2. **Strategic Recommendations:** How can Marriott improve 2-3 star hotels based on the data insights?

# <font color="purple"><u>Data Understanding and Analysis:</u></font>

The dataset we are working with contains hotel attributes, including location, size, staff roles, amenities, and ratings. To begin our analysis, we first explored the distribution of ratings across different cities, followed by the identification of key features that correlate with higher star ratings.

**Exploratory Data Analysis (EDA):**  
We began by visualizing the distribution of hotels by rating and analyzing key features for each star category.



From this initial analysis, we observed that Marriott hotels in large urban cities (like New York, Los Angeles, and Miami) tended to have 4 or 5-star ratings, while hotels located near airports or in smaller cities had ratings closer to 2 or 3 stars.

**Feature Importance Analysis:**  
To understand which features were most important for predicting a hotel's star rating, we performed a feature importance analysis using machine learning models like Random Forest.


The top features identified for improving star ratings include:
- **Amenities:** The presence of high-end amenities like steam rooms, wine/Champagne services, and laundry facilities.
- **Staff Services:** The availability of concierge services, porters, bellhops, and valet services.
- **Facilities:** Upscale facilities such as conference centers, ballrooms, private sports courts, and bar/lounges.

**Clustering Hotel Ratings:**  
To uncover more granular insights, we  clustered hotels based on similar features and ratings to identify patterns that could help inform Marriott’s strategy.


# <font color="orange"><u>Results:</u></font>

The feature importance analysis confirmed that higher-rated hotels tend to have more premium amenities, better staff services, and more extensive facilities. Our clustering also revealed that Marriott’s 2-3 star hotels often lacked high-end amenities and services, and their facilities were more basic compared to their 4-5 star counterparts.

The key findings are:
1. **2-3 star hotels** are generally lacking in premium amenities such as steam rooms, wine/Champagne services, and luxury staff services like porters and concierge.
2. **Facilities** are also a significant differentiator; Marriott’s higher-rated hotels often feature ballrooms, conference centers, and private lounges or bars.

# <font color="teal"><u>Conclusions:</u></font>

Based on our analysis, we recommend that Marriott focus on improving the following areas in their 2-3 star hotels:
1. **Enhanced Amenities:** Introduce premium amenities such as steam rooms, wine/Champagne services, and laundry services.
2. **Upgraded Staff Services:** Ensure key staff members, such as bellhops, concierge, and valet, are available at lower-rated hotels.
3. **Improved Facilities:** Invest in upscale facilities like ballrooms, conference centers, and private sports courts that align with higher-rated hotels.

By implementing these changes, Marriott can likely raise the quality of its 2-3 star hotels and potentially increase their ratings to the 4-5 star range, improving both guest satisfaction and the brand’s overall image.





