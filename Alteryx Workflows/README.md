# Alteryx Workflows 👩‍💻

- We have used Alteryx for calculating R Score, F Score, and M Score For RFM Analysis and Segmentation of customers. 
- Alteryx is used to automate data processes more quickly and efficiently. It collects, prepares, and blends data that may otherwise be time-consuming or impossible to combine using other tools. 
- Through this, Alteryx provides answers to complex business questions and can help to simplify or automate data processes. 
- This not only saves a significant amount of time, but also helps to prevent errors that may have occurred if the process were done manually.

🎯 𝑾𝒉𝒂𝒕 𝒊𝒔 𝑹𝑭𝑴 𝑨𝒏𝒂𝒍𝒚𝒔𝒊𝒔 ? 

- FM (Recency, Frequency, Monetary) analysis is a marketing technique used to segment customers based on their purchase behavior.
- It involves analyzing the recency (how recently a customer made a purchase), frequency (how often a customer makes a purchase), and monetary value (how much a customer spends) of their transactions.
- The RFM model assigns a score to each customer in each category (1-5) and then combines the scores to create a composite RFM score.
- Customers are then segmented based on their composite RFM score, with the highest-scoring customers considered the most valuable.

🎯 𝒘𝒉𝒂𝒕 𝒊𝒔 𝑹 𝑺𝒄𝒐𝒓𝒆? 𝑯𝒐𝒘 𝒕𝒐 𝒄𝒂𝒍𝒄𝒖𝒍𝒂𝒕𝒆? 

- “R” stands for Recency and refers to how recently a customer has bought. 
- Customer with most recent order are given R_SCORE AS 4
- Formula used - 
𝑰𝑭 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚]=𝟑𝟔𝟒 𝒐𝒓 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚] >𝟐𝟓𝟑 𝑻𝑯𝑬𝑵 𝟏 <br>
𝑬𝑳𝑺𝑬𝑰𝑭 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚]>= 𝟐𝟓𝟑 𝒐𝒓 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚] > 𝟏𝟒𝟓 𝑻𝑯𝑬𝑵 𝟐 <br>
𝑬𝑳𝑺𝑬𝒊𝒇 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚]>= 𝟏𝟒𝟓 𝒐𝒓 [𝑴𝒊𝒏 𝒐𝒇 𝑹𝒆𝒄𝒆𝒏𝒄𝒚] > 𝟔𝟓 𝑻𝑯𝑬𝑵 𝟑 <br>
𝑬𝑳𝑺𝑬 𝟒 <br>
𝑬𝑵𝑫𝑰𝑭 <br>

🎯 𝒘𝒉𝒂𝒕 𝒊𝒔 𝑭 𝑺𝒄𝒐𝒓𝒆? 𝑯𝒐𝒘 𝒕𝒐 𝒄𝒂𝒍𝒄𝒖𝒍𝒂𝒕𝒆?

- “F" stands for Frequency and refers to How often do they purchase?
- Customer with most frequent orders are given F_SCORE AS 4
- Formula used - 𝑰𝑭 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚]=𝟓𝟕 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚] >𝟑𝟓 𝑻𝑯𝑬𝑵 𝟒 <br>
  𝑬𝑳𝑺𝑬𝑰𝑭 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚]>= 𝟑𝟓 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚] > 𝟏𝟓 𝑻𝑯𝑬𝑵 𝟑 <br>
  𝑬𝑳𝑺𝑬𝒊𝒇 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚]>= 𝟏𝟓 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑸𝒖𝒂𝒏𝒕𝒊𝒕𝒚] > 𝟓 𝑻𝑯𝑬𝑵 𝟐 <br>
  𝑬𝑳𝑺𝑬 𝟏 <br>
  𝑬𝑵𝑫𝑰𝑭 <br>
  
🎯 𝒘𝒉𝒂𝒕 𝒊𝒔 𝑴 𝑺𝒄𝒐𝒓𝒆? 𝑯𝒐𝒘 𝒕𝒐 𝒄𝒂𝒍𝒄𝒖𝒍𝒂𝒕𝒆?

- "M" stands for Monetary Value and refers to how much do they spend?
- Customer with Max SUM_PROFIT are given M_SCORE AS 4
- Formula Used - 𝑰𝑭 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕]=𝟏𝟗𝟕𝟎 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕] >𝟓𝟎𝟎 𝑻𝑯𝑬𝑵 𝟒 <br>
  𝑬𝑳𝑺𝑬𝑰𝑭 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕]>= 𝟓𝟎𝟎 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕] > 𝟐𝟐 𝑻𝑯𝑬𝑵 𝟑 <br>
  𝑬𝑳𝑺𝑬𝒊𝒇 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕]>= 𝟐𝟐 𝒐𝒓 [𝑺𝒖𝒎 𝒐𝒇 𝑷𝒓𝒐𝒇𝒊𝒕] > -𝟐𝟐 𝑻𝑯𝑬𝑵 𝟐 <br>
  𝑬𝑳𝑺𝑬 𝟏 <br>
  𝑬𝑵𝑫𝑰𝑭 <br>

  
🎯 𝑪𝒂𝒍𝒄𝒖𝒍𝒂𝒕𝒊𝒏𝒈 𝑪𝒐𝒎𝒃𝒊𝒏𝒆𝒅 𝑹𝑭𝑴 𝑺𝒄𝒐𝒓𝒆 

- Combined RFM Score can be calculated using this formula : ([𝑹_𝑺𝒄𝒐𝒓𝒆] * 𝟏𝟎𝟎) + ([𝑭_𝑺𝒄𝒐𝒓𝒆] * 𝟏𝟎) + [𝑴_𝑺𝒄𝒐𝒓𝒆] 
- Based on the RFM Scores Customers are divided into various segments such as Platimum, Gold, Silver, and Bronze. 
- Refer to the alteryx workflow below 

  <img width="533" alt="image" src="https://user-images.githubusercontent.com/63411758/213882400-327fbf81-41d0-49e9-9348-818fb0143743.png">





