# Benchmark of automatic metrics on Automatic Story Generation :  Do results depend on correlation coefficients ?

## Goal
This repository contains the experiments related to the project on Text Similarity for the lecture of **Natural Language Processing**.
The goal of the project is to evaluate automatic metrics for Automatic Story Generation (ASG). Correlation are computing between human judgements and automatic metric scores in order to rank these metrics. Higher the correlation coefficient, better the metric. However, it exists three diffrerent correlation coeffcients : Pearson, Spearman and Kendall. The project shed light on the need to pay attention to the different cor-
relation coefficients as they rank differently the metrics.

## Structure of the repository
We used the dataset ```Hanna``` related to the paper [Of Human Criteria and Automatic Metrics:
A Benchmark of the Evaluation of Story Generation](https://arxiv.org/pdf/2208.11646.pdf) that is available in the ```Data``` directory.  

The analysis is the Notebook named ```Project```.

## Overview
First, heatmaps are ploted to see the correlations between human evaluation and metric scores. Then for each criteria, we compute the Top 5 of the best metrics depending on the correlation coefficient. Finally, we identify if the ranking of the different metrics are statistically different from a correlation coefficient to another using a Wilcoxon test.




