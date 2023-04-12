# IIT-twitter

## Preprocessing
We obtain a list of Congressional Twitter accounts here:
https://ucsd.libguides.com/congress_twitter
This list is located at data/congress_twitter_117th_combined.csv

After that, we use twarc to convert account names to user IDs. Then we use twarc to get the timelines of all congressmembers' user IDs for July-September of 2022. We do this at data/preprocess.ipynb, and the json files can be found under data/timelines/.

## Descriptive Analysis
