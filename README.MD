## Description

To run Spark on local Windows computer

1. follow setup instructions on https://medium.com/@GalarnykMichael/install-spark-on-windows-pyspark-4498a5d8d66c to set up spark on windows
2. open command prompt, not Anaconda Command prompt
3. Type: pyspark --master local[2]
4. Will open jupyter notebook with spark. This sets up spark local mode with 2 cores

Data file, Train_onetag_small.json, for 3_Machine_Learning_with_Spark can be found here:
https://drive.google.com/open?id=1FJkeOYsyBBsPvDVDAN_KZynQf6LEjXTi

Train_onetag_small.json is approximately 120mb.

Put Train_onetag_small.json in the following file structure.

```

|-- 1_Power_of_Spark
|-- 2_Data_Wrangling_with_Spark
|-- 3_Machine_Learning_with_Spark
  |-- 10_model_tuning_solution.ipynb
  |-- 1_numeric_features.ipynb
  ...
  |-- Train_onetag_small.json
  
```
