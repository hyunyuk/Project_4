# College Football to NFL Draft Project
_Project by: Amanda Krest and Tiffany Yuk_

## Project Topic, Background, Audience

#### Project Goal
Looking at a dataset about ESPN NFL players from 1967-present from Kaggle, we would like to create a model predicting which players will be picked for the next NFL players based on stats. 

<img src = "./Images/NFL logo.jpg" width="400">

#### Project Factors
* **Target Variable**
  * Overall 

* **Features**
  * Age
  * Total_qbr (adjusted total QB rating)
  * Points_added (numbers of points contributed by a QB)
  * Qb_plays (plays  on which the QB has a non-zero expected points contribution)
  * Total_epa (total expected points added with low leverage plays)
  * Pass (expected points added on pass attempts)
  * Run (clutch-weighted expected points added through rushes)
  * Exp_sack (clutch-weighted expected points lost from sacks)
  * Penalty (expected points added on penalities)
  * Raw_qbr(raw total QB rating)
  * Sack(expected points added on sacks with low leverage plays down-weighted)
  * Value(statistic value)
  * Active (active player?)
  * All_star (all-star in college)
  * Grade (player grade)
  * Weight
  * Height

#### Roles
* **Data Cleaning and Analysis**
  * Tiffany
* **Machine Learning Model**
  * Tiffany
* **Visualization**
  * Amanda

#### Technologies Used
* **Data Cleaning and Analysis**
  * Jupyter Notebook
* **Machine Learning Model**
  * Jupyter Notebook
* **Visualization**
  * Tableau Public
  
## Data Exploration and Analysis Phases
 
## ETL Method
  ### Extracting the Data
  Our data was contained from four different datasets about ESPN NFL players from 1967-present from Kaggle. In total there were over 30 columns and over 4,000 rows. 
  * College QB metrics for every quarterback since 2004
  * NFL Draft Prospects from 1967 to now
  * NFL Draft Profiles (Contained more information about the players)
  * Ids (Wasn't actually necessary)
  * College Statistics(Contained certain statistics about the players)   
  ### Transforming the Data
  We then merged the dataset and removed any nulls as well as unnecessary columns like school colors
  ### Loading the Data


## Machine Learning
  ### Model Choice
  The model we chose to use was the **Logistic Regression Model**
## Dashboard

## Conclusion

## Future Projects
* For a future project, incorporating the 'statistics' column would be a good idea. The column encompasses essential counting metrics such as tackles, receiving touchdowns, and more depending on the player's season. Having this info would make it easier to figure out which players would be a great candidate for the NFL.

