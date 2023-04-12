# IIT-twitter

## Preprocessing
We obtain a list of congressional Twitter accounts from UC San Diego at [this webpage](https://ucsd.libguides.com/congress_twitter). We use the 117th Congress in order to get congressional tweets from 2022, as the 117th Congress was active from 2021-2023. This list is located at [data/congress_twitter_117th_combined.csv](https://github.com/4Freye/IIT-twitter/blob/main/data/congress_twitter_117th_combined.csv).

After that, we use twarc to convert account names to user IDs. Then we use twarc to get the timelines of all congressmembers' user IDs for July-September of 2022. We do this at [data/preprocess.ipynb](https://github.com/4Freye/IIT-twitter/blob/main/data/preprocess.ipynb), and the json files which twarc outputs can be found under [data/timelines/](https://github.com/4Freye/IIT-twitter/tree/main/data/timelines).

## Descriptive Analysis
