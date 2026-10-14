# Airbnb-Hotel-Booking-Analysis-DIY-Project-1-

# Problem Statement of Airbnb Hotel Booking Analysis

The hospitality industry has undergone a significant transformation with the rise of online platforms facilitating short-term lodging and tourism. Leading this revolution is Airbnb, Inc., a pioneering American company that has reshaped travel accommodation through its innovative online marketplace. Established in 2008 in San Francisco, California, Airbnb provides a diverse range of lodging options, offering guests a unique and personalized experience. Unlike traditional hospitality providers, Airbnb operates on a commission-based model, facilitating transactions between hosts and guests without owning the properties listed on its platform. This research analysis delves into the New York City Airbnb dataset to extract meaningful insights. Through rigorous data cleaning, exploratory analysis, and visualization techniques, the study aims to illuminate the dynamics of the city's lodging market. By discerning factors influencing listing availability, pricing strategies, and overall customer satisfaction, the research contributes to a deeper understanding of Airbnb’s operations in one of the world's most dynamic urban environments. These insights hold significance for stakeholders and enthusiasts seeking to navigate the evolving landscape of short-term accommodation.

# Project Description of Airbnb Hotel Booking Analysis

The project consists of performing analysis on an Airbnb Open Data dataset such that we can make some inferences on property characteristics like listing feature, pricing, behaviour of hosts, reviews and availability patterns of the Airbnb properties. The data includes information about Airbnb listings in various categories that includes property types, host details, location, room types, price, service fee, minimum nights, number of reviews, last review date, review scores, host’s total listing counts and their availability details as available per year.
This is an end to end data analysis project of Airbnb Data, carried out in Python, comprising of data cleaning, exploratory data analysis (EDA), statistical analysis and data visualization to find out several interesting and useful insights from the given dataset.

# Dataset Fields

Given below are the most of the important fields of the dataset, which we have made use of this project:
ID : Unique identifier of the Airbnb listing.
Name : Name of the Airbnb listing.
Host ID : Unique identifier of the host.
Host Identity Verified : The identity of the host is verified or not.
Host Name : The name of the host.
Neighbourhood Group : The larger neighborhood containing the property.
Neighbourhood : The more specific neighborhood where the property is located.
Latitude & Longitude : The geographic coordinates (latitude and longitude) of the property.
Country & Country Code : the country the property belongs to.
Instant Bookable : Whether the listing can be booked instantly.
Cancellation Policy : The policy concerning cancellations of the listing.
Room Type : Type of accommodation offered.
Construction Year : Year in which the property was constructed.
Price : Price of the Airbnb listing.
Service Fee : The service fee charged per booking.
Minimum Nights : The minimum number of nights required to book the property.
Number of Reviews : The total number of reviews the listing received.
Last Review : Date of the last review for the listing.
Reviews per Month : The average number of reviews per month the listing receives.
Review Rate Number : Rating/review score for the listing.
Calculated Host Listings Count : The number of listings the host has calculated for this group.
Availability 365 : The number of days the listing is available throughout the year.
House Rules : Rules imposed by the listing owner or host for a stay.
License : Listing license information.


# Project Objectives

The analysis aims to answer the following questions:
1) What are the different property/room types available in the dataset?
2) Which neighborhood group has the highest number of Airbnb listings?
3)Which neighborhood group has the highest average listing price?
4)Is there a relationship between the construction year of a property and its price?
5)Who are the top 10 hosts based on calculated host listing count?
6)Are hosts with verified identities more likely to receive positive reviews?
7)Is there a correlation between listing price and service fee?
8)What is the average review rate number, and does it vary according to neighborhood group and room type?
9)Are hosts with a higher number of calculated listings more likely to maintain higher availability throughout the year?


# What is Data Wrangling ? 

Data wrangling, a crucial phase in the data analysis process, involves preparing and cleaning raw data to make it suitable for analysis. This involves various tasks such as handling missing values, removing duplicates, and transforming data into a consistent format. Effective data wrangling ensures that the data is reliable and ready for exploration, enabling meaningful insights to be derived from it.


# What is the Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA)is a vital phase in data analysis involving the examination and visualization of data to uncover patterns ,trends, and insights.in the context of an Airbnb data analysis project, EDA allows researchers to gain a Comprehensive understanding of the dataset's characteristics, distribution and relationships between variables. Through techniques such as summary stastics, data visualization ,and correlation analysis, EDA sets the stage for further investigation and hypothesis testing, uiding subsequent analytical decisions.


# Problems Identified within the Data

1) 541 duplicated Records where found in the Data. 
2) Insufficient information were recorded for the house rules and License columns. 
3) Dollar signs and commas recorded along with the values for price and service fee. 
4) The currency for price and service fee were not added to the column's titles. 
5) Missing values in some records 
6) Columns like the price, service fee, id, host id, last review, Construction year are assigned wrong datatypes. 
7) In the neighborhood group column the spelling of 'Brooklyn' was misspelt in some records. 
8) Some outliers were identified in the availability 365 column.


# End Users of this Project

The end-users of the Airbnb Hotel Booking Analysis are individuals or entities who can benefit from the information provided by the analysis in order to improve decision-making related to Airbnb listings, pricing, hosts, reviews, and availability.
1) Airbnb Hosts -Can leverage the analysis to gain insights into pricing dynamics, customer feedback, availability, and competitive landscape of specific neighborhoods. 
2) Property Owners -Can leverage the analysis to determine optimal neighborhoods, preferred room configurations, and accurate pricing for their properties. 
3) Airbnb Management -Can analyze the performance of listings, host patterns, customer ratings, service fees, and availability of various regions. 
 4) Travelers / Guests -Can compare room alternatives, costs, locations, customer reviews, cancellation terms, and availability before finalizing a reservation. 
5)  Business Analysts / Data Analysts -Can utilize the derived insights to discover patterns and correlations between pricing, service charges, guest reviews, host listings, and availability. 
6)  Marketing Teams -Can uncover popular locations, favored properties with higher ratings, traveler preferences, and pricing structures to enhance marketing strategies. 
7)  Investors -Can refer to the analysis to detect attractive locations and property traits suitable for Airbnb investments.


# Technologies Used In this Project 

Hardware Requirements
The hardware requirements for performing the Airbnb Hotel Booking Analysis are:
RAM – 8.00 GB
Operating System – Windows 11 
Processor – Intel(R) Core(TM) i3-1115g4
Processor speed – 3.00 GHz
Software Requirements
The software requirements for performing the Airbnb Hotel Booking Analysis are:
Programming Language – Python 
Development Environment / IDE – Jupyter Notebook 
Data Analysis Libraries – Pandas, NumPy 
Data Visualization Libraries – Matplotlib, Seaborn 
Dataset Format – CSV


# Results of the Project 

# Clean The Data
Steps to be Taken for Data Cleaning
1) Drop duplicated records.
2) Drop house rules and license columns with insufficient data.
3) Remove all dollar signs in the price and service fee columns.
4) Remove all commas from the price and service fee columns.
5) Rename the price and service fee columns to include a dollar signs.
6) Drop all records with missing values.
7) Change all mismatched data types to the appropriate once.
8) Correct the Spelling of 'brookin' to 'Brooklyn’
9) Get rid of outliers in the 'availability 365' column data.

<img width="973" height="1013" alt="image" src="https://github.com/user-attachments/assets/efd5f4ef-cec6-4ea2-a024-65567c352829" />

<img width="1342" height="1004" alt="image" src="https://github.com/user-attachments/assets/6437ad2c-bd87-421d-8000-dc0c2b26c1cf" />


# Q1. What are the different property types in the dataset?

<img width="1354" height="844" alt="image" src="https://github.com/user-attachments/assets/c4dbd5b0-dc54-4678-91dc-da199a2ae6dd" />


# Q2. Which neighborhood group has the highest number of listings?

<img width="1163" height="821" alt="image" src="https://github.com/user-attachments/assets/df39db47-0a28-4ea8-8084-a82f9af8ac0a" />


# Q3. Which neighborhood groups have the highest average prices for Airbnb listings?

<img width="1282" height="788" alt="image" src="https://github.com/user-attachments/assets/d6ec9d33-40a9-4935-b425-6ae0ecd6e1ab" />


# Q4. Is there a relationship between the construction year of property and price?

<img width="944" height="688" alt="image" src="https://github.com/user-attachments/assets/dbb6fc1e-5328-4996-915c-9dbf33c4f30f" />

<img width="1620" height="917" alt="image" src="https://github.com/user-attachments/assets/6fe54f14-5f6e-495c-a0a3-3b81fca86a4b" />


# Q5. Who are the top 10 hosts by calculated host listing count?

<img width="1462" height="757" alt="image" src="https://github.com/user-attachments/assets/5900be5d-bc8b-44b0-8864-4615f4d32f98" />

<img width="1518" height="989" alt="image" src="https://github.com/user-attachments/assets/593bd515-f516-4da2-9814-13553bca2db2" />


# Q6. Are hosts with verified identities more likely to receive positive reviews?

<img width="1832" height="696" alt="image" src="https://github.com/user-attachments/assets/78db00f2-22e7-47ef-ac03-78749fbfd8cb" />

<img width="1534" height="909" alt="image" src="https://github.com/user-attachments/assets/63783509-f691-486d-bd0d-9805aada1721" />


# Q7. Is there a correlation between the price of a listing and its service fee?

<img width="1453" height="791" alt="image" src="https://github.com/user-attachments/assets/dd4b86f4-4d91-45af-9fcb-61bf6c593365" />


# Q8. What is the average review rate number for listings, and does it vary by neighborhood group and room type?

<img width="1345" height="790" alt="image" src="https://github.com/user-attachments/assets/9a946471-f770-411a-bae6-1f61b4f900e0" />

<img width="1692" height="908" alt="image" src="https://github.com/user-attachments/assets/ab1ba05f-1267-4de5-95ef-f97db5f102f2" />


# Q9. Are hosts with a higher calculated host listings count more likely to maintain higher availability throughout the year?

<img width="1500" height="803" alt="image" src="https://github.com/user-attachments/assets/0b8a32d4-a3bd-46a1-9d6b-75a40f23d16e" />

<img width="1797" height="841" alt="image" src="https://github.com/user-attachments/assets/8b5e030e-6f2c-41b4-a060-63b36fe7ee48" />

# Future Scope

• Advanced Predictive Analytics: Develop more sophisticated models using machine learning to better predict booking trends and pricing strategies.
• Personalized Recommendations: Implement algorithms to provide personalized recommendations for guests based on their past behaviors and preferences.
• Dynamic Pricing Models: Create dynamic pricing models that adjust rates in real-time based on demand, competition, and market conditions.
Geospatial Analysis: Conduct in-depth geospatial analysis to understand how location factors influence booking rates and guest preferences.
• Integration with External Data: Incorporate external data sources such as local events, weather patterns, and economic indicators to enhance the accuracy of the analysis.
• Host and Guest Behavior Analysis: Analyze long-term trends in host and guest behaviors to identify shifts in the market and emerging patterns in the hospitality industry.

# Conclusion 

In conclusion, this project has provided a comprehensive analysis of the New York City Airbnb dataset, shedding light on various aspects of the short-term lodging market. Through data wrangling, exploratory data analysis (EDA), and interpretation of summary statistics, we've uncovered valuable insights into listing distribution, pricing dynamics, host, and review analysis. Key findings include the dominance in counts of Entire home/apt listings, the variability in listing counts across neighborhood groups, and the downward trend between property construction year and price. Additionally, the analysis highlighted the significance of verified host status on review rates, as well as the strong correlation between listing price and service fee. Furthermore, conducting sentiment analysis on guest reviews to understand factors driving customer satisfaction and preferences could inform targeted marketing strategies and product improvements for Airbnb. Lastly, expanding the analysis to include predictive modeling techniques, such as regression or machine learning algorithms, could enable forecasting of listing demand, pricing trends, and customer behavior, facilitating strategic decision-making for stakeholders in the short-term lodging industry.















































































































































































