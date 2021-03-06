## Analysis of two tweets from the leaders of the ALP and LNP in Australia.

The tweet thread where I posted this analysis is here: https://twitter.com/timothyjgraham/status/1513014392740540418. 

The two tweets under examination are:

1. https://twitter.com/AlboMP/status/1512657668053540864
2. https://twitter.com/ScottMorrisonMP/status/1512675612796006404

I collected all the likes for these tweets and the IDs of accounts that liked each tweet are provided in the two files in this repository.

I used 'twarc2' to collect the data: https://twarc-project.readthedocs.io/en/latest/twarc2_en_us/. For example, to collect the liking accounts for AlboMP's we use the following command:

```
twarc2 liking_users 1512657668053540864 1512657668053540864_liking_users.jsonl
```

I also provide Python code for analysing each tweet, provided in the two Jupyter Notebook files (ipynb). The python code takes as input the 'liking-users' data as shown in previous step. 

The analysis used Botometer Pro: https://rapidapi.com/OSoMe/api/botometer-pro/details.
