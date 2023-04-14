# IIT-twitter
## Introduction

## Preprocessing
We obtain a list of congressional Twitter accounts from UC San Diego at [this webpage](https://ucsd.libguides.com/congress_twitter). We use the 117th Congress in order to get congressional tweets from 2022, as the 117th Congress was active from 2021-2023. This list is located at [data/congress_twitter_117th_combined.csv](https://github.com/4Freye/IIT-twitter/blob/main/data/congress_twitter_117th_combined.csv).

After that, we use twarc to convert account names to user IDs, and then get the timelines of all congressmembers' user IDs for July-September of 2022. We do this at [data/accounts_to_timelines.ipynb](https://github.com/4Freye/IIT-twitter/blob/main/data/accounts_to_timelines.ipynb), and the json files which twarc outputs can be found under [data/timelines/](https://github.com/4Freye/IIT-twitter/tree/main/data/timelines).

## Descriptive Analysis
The [descriptive analysis notebook](https://github.com/4Freye/IIT-twitter/blob/main/descriptive_analysis.ipynb) contains visualizations and explorations into congressmembers' user behavior. The main findings from that notebook are as follows:
- The total volume of congressmembers' tweets ranges from about 6,000-10,000 times a week.
- The majority of congressmembers tweet between 10 to 20 times a week, 1 to 3 times a day, and .05 to .15 times an hour.
- Congressmembers tweet up to 4 times as much during the week than on the weekends.
- They rarely tweet at night (in EST), and tweet a lot more during the day

We also provide heatmap visualizations of a random sample of congressmembers- aggregating on the hourly level and daily level.

