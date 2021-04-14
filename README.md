D2TS
========================

D2TS: A Dual Diversity Tree Selection Approach toPruning of Random Forests
========================
Random Forest is one of the most effective classification techniques. It is an ensemble technique with typically decision trees as its classifiers. Each tree votes for an outcome when a new instance is being classified, and a majority vote is taken to decide the final output. Two main factors play an essential role in Random Forests performance, namely diversity among trees in the forest and their number. Higher diversity increases prediction accuracy, whereas lower numbers of trees result in faster predictions.This paper aims at optimizing these two factors by using clustering analysis of trees in order to prune correlated trees while keeping outlier trees to maintain diversity. Density-Based Spatial Clustering of Applications with Noise (DBSCAN) is one of the most commonly used clustering techniques and is immune to outliers. DBSCAN is adopted to group trees in clusters based on their prediction behaviour and identify outliers. Cluster and outlier representatives are the two criteria that make DBSCAN a method with a dual criteria for generating diversity among trees in a pruned ensemble. Our approach achieved up to a 99\% pruning level while resulting in a better or at least a similar accuracy to the original forest for multiple datasets with varying properties.

Running D2TS
========================
This work was implemented using Knime Analytics Platform. You can simple import the .knwf file into Knime and run it on any dataset.


Reference
========================
If you use this code as part of any published research, please acknowledge the following papers.
