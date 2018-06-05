Hi there!

If you would like to re-run the featurization and modeling process on your own computer, please use this process:
## Overview
1. Clone this repo to your computer
2. Enter the *src* directory
3. *15-20 minutes:* If you would like to re-run the featurization of the dataframe, using near-raw data stored in s3 buckets:
  - Run *featurize.py*
    - This will save the featurized dataframe to a local csv file
4. *5-10 minutes:* Run *model.py* to see detailed performance metrics of the model for predicting restaurant closure. It will also show performance using different subsets of the data, and feature importances.
5. Check out the figures that will be saved in the *plots* directory after you've run *model.py*
