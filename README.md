# Capstone

This repo explores the use of a Gradient Boosting Classifier to predict next day EURUSD foreign exchange directional price movement. Using this algorithm as a directional filter the outcomes of a momentum and a mean reversion trading strategy are compared. All data was sourced from Pepperstone Australia and can be easily replaced by your own within the code. Please see the requirements.txt for necessary packages. Please see the below workflow to understand the running order and how results were attained.



#Workflow
---
You can run the short version to replicate the results or run the entire program if you are changing the study period:



#Short version
---
Open "Capstone Momentum"

Ensure all files are saved in correct directory

Ensure all libraries are installed

Run from top to bottom

(You will be taking advantage of the pre saved ML file and the presaved and edited MomentumLONG(SHORT)1 files)



#Replicate Full Sudy
---
Open Capstone Machine Learning

Ensure all files are saved in correct directory

Ensure all libraries are installed

Run from top to bottom

Open MLResults.csv you have created

Open Capstone Momentum and Capstone Mean Reversion IPYNB's

Run part 1 of each file to generate 4 new .csv files

Open the files named MomentumLONG(SHORT) and MeanReversionLONG(SHORT).csv files

Using the prediction list in MLResults.csv as a guide remove the 1's or -1's in the position columns of the momentum and mean reversion strategies if they are trading against the directional bias given by the prediction list.

Once complete save and run the part two sections within the Capstone Momentum and Capstone Mean Reversion IPYNB's
