# sude_DSA210project
2024 DSA210 Project - Shoping Habits Project - Sude Karaahmet

The objective of this project is to analyze my credit card statements by categorizing the transactions into five distinct groups: cosmetics, food, clothing, transportation, and other. Hypothesis is that food is the highest ranking spending unit out of them all. The inclusion of the 'other' category was necessary as it accounts for purchases that did not fit into the main categories.

To gather the data, I used the QNB Mobile application. The dataset originally consists of five columns, but for the purposes of this project, I focused on the first three: the date of the purchase, the business, and the cost. The date of purchase is particularly important because transactions made through installment plans are recorded in separate months, but I believe that reflecting these purchases in the month of the initial purchase offers a more realistic view of spending behavior.

For data processing, I used Pandas, and for generating visual representations of the data, I used matplotlib.

The data collection process began with extracting my credit card statements from the QNB Mobile application in PDF format, which was then transferred into an Excel file for easier analysis. In the excel file, data was preprocessed by turning business names in to the five distinct groups(cosmetics, food, clothing, transportation, and other). I focused on processing the date column to calculate monthly expenses. In the first set of graphs, I plotted daily purchases, and I shared the month in which the highest spending occurred. The second set of graphs presented a pie chart that displayed the percentage of spending in each category, at the end I shared the highest percentage of spending. Finally, the third set of graphs illustrated the number of purchases made each day during the month, and I shared the day with the highest number of purchases.

After observing the analyzed data through visualizations (graphs and charts) the hypothesis is failed to be rejected. 
