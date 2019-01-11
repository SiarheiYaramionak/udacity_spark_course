## Description
Jupyter notebooks accompanying Udacity's PySpark course for DSND's Sparkify capstone project.

## To Run PySpark on Local Windows Computer
To run PySpark on local Windows computer, good for learning and trying out PySpark syntax:

1. Follow setup instructions on https://medium.com/@GalarnykMichael/install-spark-on-windows-pyspark-4498a5d8d66c to set up PySpark on windows
2. Open command prompt, not Anaconda Command prompt
3. Run: pyspark --master local[2]
4. Will open jupyter notebook with PySpark. This sets up PySpark local mode with 2 threads/cores

Alternatively, run: pyspark --master local[\*]

This run PySpark locally with as many worker threads as logical cores on your machine.

## Data

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
