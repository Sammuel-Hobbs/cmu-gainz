# Credit Suisse Experential Project - Fall 2018
The Heinz College Finance Club at Carnegie Mellon University networks with management from Credit Suisse Bank's New York City, New York office, and collaborates in experential learning projects. The scopes of these projects generally have the depth and breadth as of a senior/capstone graduation project, but are issued and completed in 2-4 week interval; essentially a blitz research project. 
## Application Usage Profiling
Like many large corporations with thousands of employees and offices scattered throughout the world, CS bank must find a way to provision the right tools to the right employees, and ideally with minimal delay and the most cost effective manner.  The firm wanted our CMU team to look at how CS could develop smarter, efficient provisioning of relevant \[software] applications for onboarding new hires, internal employee transfers and conversions.
## Project at a Glance
For this project, I acted primarily as the project coordinator and developed the machine learning models which consisted of *Kmeans Clustering* and *Apriori Association* (market basket analysis). 
### Data Sets
We were given two masked/anonymized datasets that captured a 6-month snapshot of applications requested by employees at CS bank. The two sets are **a) employee** data consisting of an id code, department, and geographical region and **b) application** transactional data (requester id, date, request log, etc). 
### Data Understanding and Machine Learning
Clustering analysis was performed in Python, and the association rules were developed in R.  Files associated with each were made with Jupyter and Rstudio notebooks respectively.  
#### Kmeans Clustering
**cluster_departments**
