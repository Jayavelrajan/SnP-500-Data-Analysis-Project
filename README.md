# S&P500 Data Analysis Project

# Overview
This project conducts a thorough analysis of S&P 500 stock data, exploring trends, moving averages, and correlations among tech giants, providing insights for investors.

# Table of Contents

- Installation
- Data Collection
- Data Analysis
  - Price Change Analysis
  - Moving Average
  - Closing Price Change in Apple, Netflix & Amazon Stock
  - Resampling Analysis
  - Correlation Among Tech Companies
  - Daily Change vs. Daily Returns
- Usage
- License

  # Installation

  To run this project, you need the following dependencies installed:
- pandas
- seaborn
- numpy
- matplotlib
- emoji
- plotly

  # Data Collection

  Using glob module to search CSV files and use it for our need

  ```bash
  import glob
  ```

  # Data Analysis

  ### Price Change Analysis
  Analysing the change in prices of the stock overtime
  ![image](images/priceChange.png)

  ### Moving Average
  Analysing the Moving average of the various stocks
  ![image](images/movingAverage.png)

  ### Closing Price Change in Apple, Netflix & Amazon Stock
  Analysing Closing price change in Apple stock
  ![image](images/appleClosingPricechange.png)

  Analysing Closing price change in Netflix stock
  ![image](images/netflixClosingpricechange.png)

  Analysing Closing price change in Amazon stock
  ![image](images/amazonClosingpricechange.png)

  ### Resampling Analysis
  Performing resampling analysis of closing price of Apple Stock

  #### Resampling data on Date basis
  ![image](images/positive_comments.png)
  #### Resampling data on Montly basis
  ![image](images/positive_comments.png)
  #### Resampling data on Yearly basis
  ![image](images/positive_comments.png)
  #### Resampling data on Quarterly basis
  ![image](images/positive_comments.png)

  ### Correlation Among Tech Companies
  Analysing Whether closing prices of these tech companies (Amazon,Apple,Facebook,Google,Netflix,Microsoft) are correlated 
  or not

  ## Pair Plot
  ![image](images/positive_comments.png)
  ## Heatmap
  ![image](images/positive_comments.png)

  Conclusions :
  Closing price of Google and Microsoft, Facebook and Microsoft, Google and Facebook, Amazon and Google are well 
  correlated. Closing prices have a co-relation of 0.97

  ### Daily Change vs. Daily Returns
  Analysing Whether Daily change in Closing price of stocks or Daily Returns in Stock are co-related or not

  ## Pair Grid
  ![image](images/positive_comments.png)


  ### Amazon and Google stocks has highest correlation between them
  ### Conclusion: If Amazon stocks decreases, then there is a 54% probablity that Google stocks also decreases

  # Usage

  Clone the repository:

  ```bash
  git clone https://github.com/your-username/your-repository.git
  cd your-repository
  ```
  Latest Version of Anaconda software environment is required!


 # License
 This project is licensed under the MIT License.


 

  

  
  
  
  











































  
