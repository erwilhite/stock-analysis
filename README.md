# stock-analysis

## Overview of Project

The purpose of this project was to refactor and build code in VBA to run analysis on stock information from 2017 and 2018. This information could then be used to influence decisions on which stocks to invest in. Code was built throughout the assessment for this dataset and then refactored to see if it could become more efficient.   

## Results

### Stock Results
This analysis showed that 2017 was a much better performing year for the provided stocks, with eleven of the twelve stocks showing positive returns. The following year showed a much different outcome, with only two of the twelve stocks with a positive return. TERPs was the only stock with a negative return for both years the analysis was done. 

![2017 stock performance](https://user-images.githubusercontent.com/104689576/169207714-3f24ad34-078d-4124-88ad-12eb16062ba1.png)
![2018 stock performance](https://user-images.githubusercontent.com/104689576/169207775-8a16ca6d-714b-4837-9480-8d91a38f1635.png)


### Script Differences
The original script was performed using a nested loop to run through the ticker array, and for each ticker calculating the volume, starting prices, and ending prices before moving on to the next ticker to perform the same analysis. The refactored code had a similar structure, but instead of using a nested loop, it made arrays of the volumes, starting prices, and ending prices, and used an index of the tickers to run through the data. 
By changing the structure of the code and the way the data was reviewed, the refactored code was able to decrease the time it took to perform the analysis. 

Original Script and Times:

![Original_2018](https://user-images.githubusercontent.com/104689576/169208166-1e14e3a6-e5fa-4089-a284-8ffe99fc8842.png)
![Original_2017](https://user-images.githubusercontent.com/104689576/169208075-9e7078fa-9097-40c1-9623-2f4471a9c976.png)
![Original_2018](https://user-images.githubusercontent.com/104689576/169208110-57d4c081-350a-45fb-aaf6-6fd62cce275f.png)

Refactored Script and Times:
![Refactored Code](https://user-images.githubusercontent.com/104689576/169208231-bd6cd6bb-8f6c-401d-b3a9-0114bb1e3b13.png)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/104689576/169208266-cc10961c-8c1d-43c5-95cc-e0780c6153dd.png)
![VBA_Challege_2018](https://user-images.githubusercontent.com/104689576/169208296-70df70cb-3741-4f43-8017-cd6586cbded6.png)

## Summary

In conclusion, refactoring code can drastically cut down the amount of calculation and loops done through a dataset, subsequently reducing the amount of time and energy needed to retrieve the intended results. This can allow for more data to be analyzed and improve efficiency of operations, particularly with large, complex data sets. However, refactoring code can take a large amount of time and energy as well, so the benefits must be weighed with the cost. It can be disadvantageous to spend the time to refactor code to improve efficiency if it does not drastically improve the results, such as in cases where the dataset might not be that large. For this dataset, it might not have been worth the time spent to refactor the code and improve the time it took to run from nine tenths of a second to one and a half tenths of second. 
