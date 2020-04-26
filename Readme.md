### Creation Date
17.04.2020

### Title
Data Wrangling Project

### Description
This is a Data Wrangling project, completion of which is required as part of a Data Analyst Nano-degree offered by Udacity.
The tasks in this project are as follows:

- Data wrangling, which consists of:
 - Gathering data
 - Assessing data
 - Cleaning data
- Storing, analyzing, and visualizing the wrangled data
- Reporting on :
 - Data wrangling efforts
 - Data analysis and visualizations

### Gathering Data for this Project
The dataset that will be wrangled (and analyzed and visualized) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.

- twitter_archive_enhanced.csv:
  The WeRateDogs Twitter archive
- image_predictions.tsv:
  The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network
The file is hosted on Udacity's servers and should be downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
- tweet_json.txt :
  Each tweet's retweet count and favorite ("like") count at minimum, and any additional data is to be queried  from Twitter API using Python's Tweepy library. The data extracted is then stored in a file called tweet_json.txt file and later read line by line into a pandas DataFrame with tweet ID, retweet count, and favorite count.

### Assessing Data for this Project
After gathering each of the above pieces of data, data is assessed for quality and tidiness issues. Issues are detected and documented wrangle_act.ipynb Jupyter Notebook.
Storing, Analyzing, and Visualizing Data for this Project
Clean DataFrame(s) are stored in a CSV file with the main one named twitter_archive_master.csv. If additional files exist because multiple tables are required for tidiness, name these files appropriately.
Data is analyzed and visualized in wrangle_act.ipynb Jupyter Notebook. 3 insights and 1 visualization are produced.

### Reporting for this Project
- wrangle_report.html
  This report  briefly describes wrangling efforts.
- act_report.html  
  This communicates the insights and displays the visualization(s) produced from wrangled data.

