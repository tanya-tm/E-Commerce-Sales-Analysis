# Alteryx Workflows 

- We have used Alteryx for calculating R Score, F Score, and M Score For RFM Analysis and Segmentation of customers. 
- Alteryx is used to automate data processes more quickly and efficiently. It collects, prepares, and blends data that may otherwise be time-consuming or impossible to combine using other tools. 
- Through this, Alteryx provides answers to complex business questions and can help to simplify or automate data processes. 
- This not only saves a significant amount of time, but also helps to prevent errors that may have occurred if the process were done manually.

🎯 What is RFM analysis ?

- FM (Recency, Frequency, Monetary) analysis is a marketing technique used to segment customers based on their purchase behavior.
- It involves analyzing the recency (how recently a customer made a purchase), frequency (how often a customer makes a purchase), and monetary value (how much a customer spends) of their transactions.
- The RFM model assigns a score to each customer in each category (1-5) and then combines the scores to create a composite RFM score.
- Customers are then segmented based on their composite RFM score, with the highest-scoring customers considered the most valuable.

🎯 what is R Score ? How to calculate ? 

- “R” stands for Recency and refers to how recently a customer has bought. 
- Customer with most recent order are given R_SCORE AS 4
- Formula used - <br>
- IF [Min of Recency]=364 or [Min of Recency] >253 THEN 1 <br>
ELSEIF [Min of Recency]>= 253 or [Min of Recency] > 145 THEN 2 <br>
ELSEif [Min of Recency]>= 145 or [Min of Recency] > 65 THEN 3 <br>
ELSE 4 <br>
ENDIF <br>

🎯 what is F Score ? How to calculate ?

- “F" stands for Frequency and refers to How often do they purchase?
- Customer with most frequent orders are given F_SCORE AS 4
- Formula used - <br> 
- IF [Sum of Quantity]=57 or [Sum of Quantity] >35 THEN 4 <br>
  ELSEIF [Sum of Quantity]>= 35 or [Sum of Quantity] > 15 THEN 3 <br>
  ELSEif [Sum of Quantity]>= 15 or [Sum of Quantity] > 5 THEN 2 <br>
  ELSE 1 <br>
  ENDIF <br>
  
🎯 what is M Score ? How to calculate ?

- "M" stands for Monetary Value and refers to how much do they spend?
- Customer with Max SUM_PROFIT are given M_SCORE AS 4
- Formula Used - <br> 
- IF [Sum of Profit]=1970 or [Sum of Profit] >500 THEN 4 <br>
  ELSEIF [Sum of Profit]>= 500 or [Sum of Profit] > 22 THEN 3 <br>
  ELSEif [Sum of Profit]>= 22 or [Sum of Profit] > -22 THEN 2 <br>
  ELSE 1 <br>
  ENDIF <br>
  
🎯 Calculating Combined RFM Score 

- Combined RFM Score can be calculated using this formula : 
- ([R_Score] * 100) + ([F_Score] * 10) + [M_Score]
- Based on the RFM Scores Customers are divided into various segments such as Platimum, Gold, Silver, and Bronze. 
- Refer to the alteryx workflow below 

  <img width="533" alt="image" src="https://user-images.githubusercontent.com/63411758/213882400-327fbf81-41d0-49e9-9348-818fb0143743.png">





