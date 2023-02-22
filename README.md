# Global-Terrorism-Analysis
The objective of this work is to analyze the region and country of a terrorist attack using exploratory data analysis, in order to acquire valuable information about the predicted attacks and attackers.
# Problem Statement

Data provided by the Global Terrorism Database.csv file is in unformatted manner, uneven data, and duplicate data and also some data columns it is irrelevant, because it’s a piled-up data coming from various different countries. For doing the analysis on the data the data needs to be in correct format and well organized formed The main objective of the analysis is to obtain the meaning full information and facts from the given huge datasets, by cleaning the datasets, doing a proper analysis and visualization and plotting the useful information into different graph and charts so that the trend and relationship between the various indicators on which the analysis is done can be understand easily.


# Dataset

The dataset contains data of more than 180000 terrorist events(no. of rows) happened since 1970 and has over 135 variables (no. of columns) describing each attack. Some of the key attributes consisting those variables which are taken under consideration for this project are listed below:

● Attacktype1_txt :

Attacktype1_txt consists of categories like explosion, armed assault, assassination, kidnapping, unarmed assaults.

● Target1_txt : Target1_txt consists of categorical values like private citizens, military, police, government officials, transportation, education, religious institution, airports, etc

● Success : ‘1’ if attack was a success. ‘0’ if the attack was a failure.

● Multiple : Value for the number of attacks happened in a single terrorist event.

● Natlty1 : Nationality of the attacker

● Weaptype1 : Type of weapon used in the attack. Weaptype1 contains values like firearms, explosives, melee, vehicles etc.

● Nkill : Number of people killed in any event

● Nwonded : Number of people wounded in any event

● Gang_type : Organization that claimed responsibility of an attack

● Region_txt : Name of the region where the attack happened.

Region_txt consists of values like East Asia, South Asia, Western Europe, etc.

● Longitude :Longitude of the location

● Latitude : Latitude of the location

● Property : Total property damage happened in any event.

● Motive Known motive of the attacker

● Day, month, year : Calendar details of the event.

●Note : For the better interpretability we had name converted those attributes in simple manner.

# Steps involved:

● Exploratory Data Analysis

After loading the dataset we performed this method by comparing our target variable that is Surge_Pricing_Type with other independent variables. This process helped us figuring out various aspects and relationships among the target and the independent variables. It gave us a better idea of which

feature behaves in which manner compared to the target variable.

● Null values Treatment

Our dataset contains a large number of null values which might tend to disturb our accuracy hence we dropped them at the beginning of our project inorder to get a better result.

● Encoding of categorical columns

We used One Hot Encoding to produce binary integers of 0 and 1 to encode our categorical features because categorical features that are in string format cannot be understood by the machine and needs to be converted to numerical format.

● Feature Selection In these steps we used algorithms like ExtraTree classifier to check the results of each feature i.e which feature is more important compared to our model and which is of less importance. Next we used Chi2 for categorical features and ANOVA for numerical features to select the best feature which we will be using further in our model.

● Standardization of features

Our main motive through this step was to scale our data into a uniform format that would allow us to utilize the data in a better way while

performing fitting and applying different algorithms to it.

The basic goal was to enforce a level of consistency or uniformity to certain practices or operations within the selected environment.

# Conclusions :

•	Most of the attacks were done on year 2014.

•	Taliban is the most active terrorist group in the world.

•	Iraq is the most affected country from terrorism because most of the peoples killed in Iraq. In Iraq a maximum of 1570 people killed in a single attack.

•	The Middle East and North Africa have the highest number of attacks followed by South Asia and South America. Terrorism here does not show an equal distribution among all regions.

•	Private Citizens and property military is the most target type as per the dataset.

•	It seems that explosives were used in around 48.6% of the attacks, followed by Armed Assault accounted for 23.5% of the attacks.

