# Data Visualization of Prosper Loans Data
## by Deepti Pradeep


## Dataset
The data consists of 113937 records of loan data with 81 parameters. Out of which 20 columns which were not of use were deleted in the process of data cleaning.The dataset was downloaded from the Udacity server.


## Summary of Findings

Various parameters such as term, employment status, prosper score, prosper rating (numeric), ccredit score upper range were analyzed with borrower rate of interest. It was observed that all these parameters were negatively correlated with borrower rate except term was slightly positively correlated. While seeing the relationship of prosper rating (numeric), it can be seen that there were a lot od people who had a median rating of between 4 and 5 and correspondingly had a borrower rate between 0.15 and 0.20. This meant that prosper rating although was highly negatively correlated it was difficult to conclude that the parameter alone could impact borrower rate of interest. On further analysis with prosper score and prosper rating(numeric) with borrower rate of interest, it became more evident that a higher prosper score and prosper rating would result in a lower borrower rate of interest and vice versa.

Another interesting factor that was noticed is employment status seemed to impact the borrower rate of interest. But when other factors such as prosper rating and employment status together were considered, employment status didn't seem to matter to impact the borrower rate of interest.


## Key Insights for Presentation

A higher prosper score and prosper rating (numeric) can result in a lower borrower rate of interest.


## Resources
Prosper data dictionary
Stackoverflow - https://stackoverflow.com/questions/38082602/plotting-multiple-different-plots-in-one-figure-using-seaborn
Lessons on data visualization from Udacity