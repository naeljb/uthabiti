1. Project Description: Provide a brief summary of your project and what it does. This will help readers quickly understand what your project is all about.

In December 2022, Save the children Uganda conducted a joint beneficiary registration and baseline of a BHA's funded food security project, Uthabiti. Unsupervised Machine Learning algorithms were applied to complement the baseline report for an in-depth understanding of the household selected, particularly the refugees.   The primary purpose was to do a segmentation analysis to find similar groups of refugee households based on key food security indicators and demographic characteristics, as well as to identify if there were refugee households significantly different from the rest of the data.

Three scenarios of variable combination were constructed for conducting this analysis. Two BHA's food security indicators (reduced Coping Strategy Index and Food Consumption Score) listed in Uthabiti's Indicator Performance tracking table (IPTT) were considered in the first scenario. In the second scenario, Food Expenditure Share (as a proxy of income) was computed and added to the variables considered under the first scenario. The third scenario included the household size and the BHA's gendered household classification in the second scenario.  

After conducting a series of data cleaning, shaping, and feature engineering tasks, an Exploratory Data Analysis (EDA) was performed. Then, the two most popular clustering algorithms (K-Means and DBSCAN) using the optimum number of clusters/groups detected by each algorithm were run for each scenario. Finally, silhouette and calinski harabasz score were computed and used to compare the quality of the clusters obtained under each scenario and to suggest the model that best fits the primary objective of this analysis. Python programing language was used to conduct the EDA and run clustering algorithms.  



2. Installation instructions:  Project is done in Python using Jupyter Notebook.  


3. Usage instructions: N/A


4. Columns and Features: 

The dataset used for this project can be found at : https://raw.githubusercontent.com/naeljb/uthabiti/main/refugee_df.csv 

The dataset consits of 541 rows with 254 columns. The columns of interest for this project are:

	hh_size :  household size

	rCSI:  reduced coping strategy index. It  measures the extent to which a household are employing coping mechanism when food is lacking. The score ranges from 0 to 56, with higher scores indicating higher food insecurity. 

	FCS:   Food Consumption Score. The Food Consumption Score (FCS) is a tool used to measure the food consumption and dietary diversity of individuals or households. It is a composite score that assesses both the quantity and quality 	of the food consumed, based on a set of food groups and frequency of consumption. The FCS can be used to determine the level of food security and to identify individuals or households that are at risk of malnutrition or 	undernutrition. The score ranges from 0 to 112, with higher scores indicating better food consumption and dietary diversity. The FCS is widely used by international organizations, governments, and researchers as a key indicator of 	food security and nutrition status.

	spend_food :  $ amount spent by the household for food purchase

	spend_cooking:  $ amount spent by the household for purchasing item for food preparation

	spend_energy_lighting: $ amount spent by the household for energy lightning 

	spend_health: $ amount spent by the household for health

	spend_education : $ amount spent by the household for education

	spend_other: $ amount spent by the household for other 

	service_Individual_financial:  Capture if the individual has received financial services

	groupmember_Savings groups:  Captures if the individual is a member of a saving groups

	received_business_training: Capture if the individual has received business training 

	Recevieved busines investment opportunities information:  Capture if the individual has received  information on business investment opportunities 


5. Contribution guidelines: Cloning and forking  allowed 


6. License information: 

This project is licensed under the Apache License 2.0.  For a complete information about the license, please go   the https://github.com/naeljb/uthabiti/blob/main/LICENSE


7. Contact information:  

For information in case you need to get in touch with the  project manager, please contact Nael Jean-Baptiste at njean@savechildren.org .  He is currently providing service as  a Monitoring and Evaluation Advisor at Save the Children







