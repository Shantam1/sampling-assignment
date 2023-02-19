# Sampling-assignment
# Comparing Sampling Techniques for 5 Machine Learning Models

## Introduction

The objective of this assignment is to investigate the efficacy of various sampling methods in generating a balanced dataset for a machine learning model. The original dataset is imbalanced, therefore random over-sampling and under-sampling techniques are utilized to create a balanced dataset. Afterward, five distinct sampling techniques are applied to this balanced dataset, and their accuracies are compared using five different machine learning models.

## Sampling Techniques

The following five sampling techniques were used in this project:

1. **Simple Random Sampling:** This is a straightforward sampling method in which every data point in the dataset has an equal chance of being chosen for the sample.

2. **Stratified Sampling:** Stratified sampling is a sampling method where the population is divided into subgroups or strata based on a particular characteristic, and samples are selected from each stratum in proportion to the population size.

3. **Systematic Sampling:** Systematic sampling is a sampling technique where a fixed interval value of n is used to select every nth element in the population for the sample.

4. **Cluster Sampling:** Cluster sampling is a sampling technique that involves dividing the population into clusters, and then randomly selecting a sample of clusters. Afterward, all individuals within the selected clusters are included in the sample.

5. **Convenience Sampling:** Convenience sampling is a non-probability sampling technique in which the sample is selected based on its convenience to the researcher, rather than a random or structured selection process.

## Comparison Table

The following table displays the accuracies of five distinct machine learning models for each sampling technique. All models use a balanced version of the original unbalanced dataset:

![Screenshot][SCREEN.png]

We can draw the conclusion from the above results that **Cluster Sampling** performs the best on all five models. Simple random sampling performs the worst on all five models. The other sampling techniques have varying performance depending on the model. The model which gives the best accuracy for all 5 samples is Decision Tree.

## Conclusion

It is recommended to use cluster sampling for this dataset, as it consistently gives the best performance across all models. However, other sampling techniques may be worth considering for different datasets or models.
 
