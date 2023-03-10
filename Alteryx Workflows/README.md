# Alteryx Workflows ð©âð»

- We have used Alteryx for calculating R Score, F Score, and M Score For RFM Analysis and Segmentation of customers. 
- Alteryx is used to automate data processes more quickly and efficiently. It collects, prepares, and blends data that may otherwise be time-consuming or impossible to combine using other tools. 
- Through this, Alteryx provides answers to complex business questions and can help to simplify or automate data processes. 
- This not only saves a significant amount of time, but also helps to prevent errors that may have occurred if the process were done manually.

## ððµð®ð ð¶ð ð¥ ð¦ð°ð¼ð¿ð²? ðð¼ð ðð¼ ð°ð®ð¹ð°ðð¹ð®ðð²? 

- âRâ stands for Recency and refers to how recently a customer has bought. 
- Customer with most recent order are given R_SCORE AS 4
- Formula used - ð°ð­ [ð´ðð ðð ð¹ðððððð] = ððð ðð [ð´ðð ðð ð¹ðððððð] > ððð ð»ð¯ð¬ðµ ð ð¬ð³ðºð¬ð°ð­ [ð´ðð ðð ð¹ðððððð] >= ððð ðð [ð´ðð ðð ð¹ðððððð] > ððð ð»ð¯ð¬ðµ ð 
ð¬ð³ðºð¬ðð [ð´ðð ðð ð¹ðððððð] >= ððð ðð [ð´ðð ðð ð¹ðððððð] > ðð ð»ð¯ð¬ðµ ð ð¬ð³ðºð¬ ð ð¬ðµð«ð°ð­ 

## ððµð®ð ð¶ð ð ð¦ð°ð¼ð¿ð²? ðð¼ð ðð¼ ð°ð®ð¹ð°ðð¹ð®ðð²? 

- âF" stands for Frequency and refers to How often do they purchase?
- Customer with most frequent orders are given F_SCORE AS 4
- Formula used - ð°ð­ [ðºðð ðð ð¸ððððððð] = ðð ðð [ðºðð ðð ð¸ððððððð] > ðð ð»ð¯ð¬ðµ ð ð¬ð³ðºð¬ð°ð­ [ðºðð ðð ð¸ððððððð]>= ðð ðð [ðºðð ðð ð¸ððððððð] > ðð ð»ð¯ð¬ðµ ð 
  ð¬ð³ðºð¬ðð [ðºðð ðð ð¸ððððððð] >= ðð ðð [ðºðð ðð ð¸ððððððð] > ð ð»ð¯ð¬ðµ ð ð¬ð³ðºð¬ ð ð¬ðµð«ð°ð­ 
  
## ððµð®ð ð¶ð ð  ð¦ð°ð¼ð¿ð²? ðð¼ð ðð¼ ð°ð®ð¹ð°ðð¹ð®ðð²?

- "M" stands for Monetary Value and refers to how much do they spend?
- Customer with Max SUM_PROFIT are given M_SCORE AS 4
- Formula Used - ð°ð­ [ðºðð ðð ð·ððððð] = ðððð ðð [ðºðð ðð ð·ððððð] > ððð ð»ð¯ð¬ðµ ð ð¬ð³ðºð¬ð°ð­ [ðºðð ðð ð·ððððð] >= ððð ðð [ðºðð ðð ð·ððððð] > ðð ð»ð¯ð¬ðµ ð 
  ð¬ð³ðºð¬ðð [ðºðð ðð ð·ððððð] >= ðð ðð [ðºðð ðð ð·ððððð] > -ðð ð»ð¯ð¬ðµ ð ð¬ð³ðºð¬ ð ð¬ðµð«ð°ð­

##  ðð®ð¹ð°ðð¹ð®ðð¶ð»ð´ ðð¼ðºð¯ð¶ð»ð²ð± ð¥ðð  ð¦ð°ð¼ð¿ð² -  

- Combined RFM Score can be calculated using this formula - ([ð¹_ðºðððð] * ððð) + ([ð­_ðºðððð] * ðð) + [ð´_ðºðððð] 
- Based on the RFM Scores Customers are divided into various segments such as Platimum, Gold, Silver, and Bronze. 
- Refer to the alteryx workflow below 

  <img width="533" alt="image" src="https://user-images.githubusercontent.com/63411758/213882400-327fbf81-41d0-49e9-9348-818fb0143743.png">





