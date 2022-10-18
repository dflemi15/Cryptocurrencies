# Cryptocurrencies

## Overview of the analysis

The purpose of this analysis was to investigate the viability of several cryptocurrencies for investment banker, Accountability Accounting. The analysis was conducted utilizing a variety of unsupervised machine learning techniques. 

## Results
After cleaning the data to remove null values and filtering it for the required information, a PCA model was crafted using 3 principal components. That information was then used to create a elbow curve to identify the best value for k. The diagram is as follows:

![image](https://user-images.githubusercontent.com/107585908/196563396-78ae251e-af44-4c95-816b-23b6eb18d851.png)

According to the diagram, four was identified as the best value for k. This due to the significant reduction in slope decline after this value in our elbow chart.
Once the k means model was initiated, a 3D diagram was produced to show the clustering of the currencies in the dataset:

![image](https://user-images.githubusercontent.com/107585908/196563420-d9f22acc-7e4a-4e97-a994-ce8a3ea3804c.png)

The data was then scaled and then placed onto 2D scatter plot to further demonstrate the distribution of the data.

![image](https://user-images.githubusercontent.com/107585908/196563458-0f9fcdfc-586b-4bf9-9a9f-d6f6bcc84389.png)

## Summary

The insight provided by this study could be invaluable for Accountability Accounting when crafting their cryptocurrency offer to their shareholders. The full method can be viewed in the “crypto_clustering.ipynb” file uploaded to the repository. 
