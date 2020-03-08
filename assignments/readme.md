# Pandas: Data Cleaning & Preliminary Analysis

   Cleaning datasets is an integral part of Data Science -- whether it involves heavy computations like parsing tick, 
imputing missing values, or simply cleaning up some manually recorded data (like this example!) for further study.  
Preparing data so it's able to be interpreted by PC's is the most important (and tedious) portion of Machine Learning Modelling, 
and it's the first step before providing any real analysis on the dataset.  It's incredibly important to be comfortable enough in 
Pandas DF manipulation so this step doesn't stop your work in it's tracks.  
I've included a monthly report of a live system -- this is a task I literally do on a monthly basis to determine which instruments
and systems are performing best, and later optimize to find which symbols I should drop, and which are vital to performance.


### -- Import the Omni-2 excel file, and create a DF with the October 2019 PNL's for instruments.

### -- Ensure datatype is proper format, and set index to date (in datetime format)

### -- Calculate summary statistics (info, describe), and remove any NaN values in *method best suited to application.*

### -- Recreate Equity curves based on identical and independent starting balances (Each instrument begins with 10k balance)

### -- Calculate returns
  #### - Bonus: Calculate Log Returns

### -- Practice using iloc and loc 
   - Create slice of returns for October 8th
   - Create slice of FULL df for days when Roku was positive.
   - Create slice of DF for days when Roku and Tsla was positive, only returning Date, Tsla and Roku columns.
   - Bonus: Create slice of DF for days when Roku was positive, Tsla was negative, and return columns beginning with r (NOT JUST RETURNING ROKU)

### -- Bonus: Calculate Correlation Matrix
   - Print Average Correlations for Each Instrument (Column)
   - Find Minimum Correlation
   - Print Minimum Correlation Pair -- (hint: I used sort to find 1st symbol and loc to find 2nd ticker)
   - Print heatmap of correlation matrix (hint: easy using seaborn package)
  
  

  
