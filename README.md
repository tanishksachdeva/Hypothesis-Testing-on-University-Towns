# Hypothesis-Testing-on-University-Towns 
Testing a hypothesis on the effect of recession on housing prices in university towns

To test the hypotheses that the university towns have their mean housing prices less effected by recessions, the notebook runs a t-test using scipy.stats.ttest_ind to compare the ratio of the mean price of houses in university towns the quarter before the recession starts compared to the recession bottom vs the same price ratio for other towns.

This is part of an assignment for the the online course Introduction to Data Science in Python. A university town here means a city which has a high percentage of university students compared to the total population of the city. The data files used here can be found at:

The list of university towns in the United States from wikipedia has been copy and pasted into the file university_towns.txt in the repo.
The housing data from the Zillow research data site stored in the file City_Zhvi_AllHomes.csv.
The GDP over time of the United States from the Bureau of Economic Analysis, US Department of Commerce, stored in the file gdplev.xls
