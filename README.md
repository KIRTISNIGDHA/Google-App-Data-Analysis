# Google-App-Data-Analysis
The data from Google Play Store App is analysed to identify new  avenues for App development. 

## Motivation
The project analyzes the apps avaialble on Google Play Store.We only analyse apps that are free to download and install. For such apps the  main source of revenue consists of in-app ads. This means the revenue for any given app is mostly influenced by the number of users who use the app. So, the more users that see and engage with the ads, the better. Our goal for this project is to analyze data to help developers understand what type of apps are likely to attract more users.

## Installation
### Dataset
The dataset used in this project can be downloaded from [Google Play Store Apps Data](https://www.kaggle.com/lava18/google-play-store-apps/home). This dataset contains data about approximately 10,000 Android apps from Google Play and it was collected in August 2018. 
- Download (~2mb file) and save it in the folder where the Jupyter notebook is also located. This will help in accesing the data easily. 
- If stored in different folder, it can be accessed by using cd. 

### Requirements
1. Python 3. 
2. Jupyter notebook (optional)
Both of them were installed using Anaconda distribution. 

## Steps of Data analysis
While analysing the data, following steps were performed. 
1. Opening and reading the data. (the reader method from csv was imported)
2. Identifying wrong data and removing it - to isolate amy data which is not in proper format.
3. Data Cleaning: 
   1. Identify any duplicated data and remove it.
   2. Remove non English characters from the dataset. only apps targeted towards english speaking population to be used.
   3. Isolate free apps from paid apps because we are only analyzing free apps generating revenue from in-app ads.
4. Identifying most common apps by genre based on average number of installations
5. Draw conclusion which category of apps can be developed to generate more revenue.

## Overall conclusion
This analysis provided insight into untapped opertunity related to medical domain mainly involving various tracking apps. 

## Future Direction
This can be used to analyse app data based on user rating. Also, apps for each category can be evaluated to identify any potential app development. 
