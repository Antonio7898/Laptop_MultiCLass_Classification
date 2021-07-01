# Laptop_MultiCLass_Classification

On the basis of price range Laptop can be categorized under following classes :

1. Entry-Level ( < 40K)
2. Main Stream ( 40K - 110K )
3. Premium     ( 110K < )

( NOTE : Price range in INR )

Considering this I build a dataset with following structure :

SPEED	| RAM | STORAGE | GPU | CLASS
----- | --- | ------- | --- | -----
1.2 |	8 | 1000 | 0 | 1

__SPEED__ - Speed of Processor in GegaHertz

__RAM__  - Random Access Memory in GB

__STORAGE__ - Either HDD/SSD in GB

__GPU__ - Graphic card Memory in GB

__CLASS__  - As described above , can be 1/2/3.


I have trained my dataset with  __RANDOM FOREST CLASSIFIER__  for this Multi Class Classification where

* Training data consist of SPEED , RAM  ,  STORAGE and GPU 
* Test data contains CLASS


