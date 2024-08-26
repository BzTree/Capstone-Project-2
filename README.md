# Capstone-Project-2

## EDIT 26/8/2024:

Added 2nd_Capstone_Project_Ver2, which:
- Adds a note explaining why Order ID was dropped.
- Adds explanations directly below the scatterplots analyzing the effect of discounts on transaction count, profits, sales and quantities bought.
- Adds extra suggestions at the end of the document, which gets it up to speed with the video presentation.

Copy-pasted original notes from 2nd_Capstone_Project.ipynb and the notes added from 2nd_Capstone_Project_Ver2.ipynb to the README, which are:
- The dataframe analyzed goes from 4 Jan 2020 to 31 Dec 2023.
- We focus only on the effect of discounts on profits and transaction count here.
- We will assume that ‘Sales’ refers to gross income, before discount is applied.
- We only group the data by country and companies, as there are enough unique values in those categories to ensure the correlations aren’t affected badly by outliers.
- The Profit/Loss and Sales Columns have no Currency sign. To avoid misrepresenting this dataset, I have not added any myself.
- In order to simplify the calculations and allow for more informative kinds of analyses, such as the point at which discounts stop being profitable and where exactly discounts mostly congregate, all transactions in this dataframe will be counted as its separate transaction, ignoring Order ID (which will be dropped).

The video presentation (via the link) and the presentation file in this Github are not updated.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## This repository is built for the purpose of containing the files needed for Capstone Project 2 of JCDSOL15.
The following files are available in this repository:
- .ipynb notebook containing the whole process of processing and analyzing the data, from understanding to cleaning to analysis and visualization.
- The presentation to better visually assess the analysis.
- This README, containing the summary of this repository.

In this analysis, the processing of the dataset can be summarized as follows:
- The dataset shows the transaction list of a large SaaS Company operating in countries all over the world.
- The analysis focuses on finding the link between discounts and profits, sales, number of transactions and quantities purchased.
- Data points are seen from the prespective of both the list of the companies and countries present in the dataset.
- The analysis ends with next steps recommended for the SaaS Company.

This project also has a video presentation (link: https://drive.google.com/file/d/1YC9l-leI7YIhTd3WEEPwYbRxonYE-KVI/view?usp=sharing) and a dashboard in Tableau Public (link: https://public.tableau.com/views/CapstoneProject_17245261337290/EffectofDiscountsonProfitsNumberofTransactionsandQuantitiesPurchased?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) that can be freely accessed.

This file is also available in this Google Drive: https://drive.google.com/drive/folders/1me686buqQ051UtqjxfgkVuyEoYEQJt_9?usp=sharing
