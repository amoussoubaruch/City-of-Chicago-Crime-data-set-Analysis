# City-of-Chicago-Crime-data-set-Analysis

> Website API : https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2

> Downloads data and put data in hdfs

```sh
$ nohup wget https://data.cityofchicago.org/api/views/ijzp-q8t2/rows.csv?accessType=DOWNLOAD
$ hdfs dfs -put rows.csv?accessType=DOWNLOAD /tmp/datafile/chicago
```
