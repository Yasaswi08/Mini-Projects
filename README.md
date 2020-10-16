# Mini-Projects

## AV Safety Analysis with Naive Bayes model
The idea was to analysze the dataset with instances of accidents or disengagements caused in the road testing of automated vehicle. I used statistical and probabilistic approaches to evaluate how well these AI-driven decision and control of AVs works under a variety of conditions and developing insights into why/how they disengage. I've started with simple tasks like basic statistic analysis and probabilistic analysis on the datasets. At the end, a Naive Bayes classifier was created to predict the cause of any unknown accidents. Alongside, few relevant visualizations were created for better understanding of the results.

## Unsupervised Stool Sample Analysis in Hepatic Encephalopathy
In this project, I wanted to study the connection between brain and gut in context of Hepatic Encephalopathy, which is a condition in the brain that results from liver cirrhosis. To study relative abundance data for microbes in stool samples collected from two sets of patients: those with cirrhosis but not HE (0), and those with cirrhosis who have developed HE (1). We want to identify microbes with significantly altered abundance levels between both populations and the ways in which these abundance levels change. Although such results will not directly answer the question of how HE develops in cirrhosis patients, they can help scientists and doctors to better direct their experimentation on how to map out the gut-brain axis.

I've started with data standardization and viusals to better understand the data at hand. Statistical analysis was then performed. Dimensionality Reduction alogithms like Pricipal Component Ananlysis(PCA) and t-Distributed Stochastic Neighbor Embedding(t-SNE) were implemented. Finally, clustreing was performed to identify various subpopulations in samples using K-Means and Gaussian Mixture Model Clustering.

## Application of Data Analysis & Factor Graphs in HPC Security
The goal of this project was to understand the progression of a multi-stage attack that aims to leak secret keys from the target system. In this project, I performed data analysis of a multi-stage attack recreated from publicly available information on the Equifax breach. I explored the use of signature-based, anomaly-based, and factor graph-based analysis techniques. As datasets were .pcap files, pyshark was used to complete the project. I've implemented the follwing tasks on the dataset:
0. Parsed the raw data into a more analysis-friendly format and identifing attack related files
1. Compared the attacker’s behavior to legitimate users’ behavior
2. Built a simple factor graph for a single event and a single attack stage
3. Extended the factor graph to capture the evolution of a series of events to infer the attack state (hidden) and decide the action to take

##
None of the datasets were included, as I am not at authority to do so.
