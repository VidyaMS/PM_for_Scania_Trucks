# PM_for_Scania_Trucks
Failure of components of APS system prediction.

This repo is for the analysis of APS data records of Scania trucks. The data consists of 170 anonmyized sensor data and a target feature which stands for failure/non failure of a component of APS system. 

Our task is to classify this data to the best accuracy . It is an imbalanced data classification where the emphasis is to arrive at the least mis-classification cost. This cost is calculated as follows : 
$500 for every record that is supposed to be a 'failure' but predicted as 'non-failure' 
$10 for every record that is supposed to be a 'non-failure' but is predicted as 'failure'.


