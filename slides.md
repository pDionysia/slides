# Bake off redux: a review and experimental evaluation of recent time series 
# classification  algorithms
Matthew Middlehurst, Patrick Schafer, Anthony Bagnall (2024) <br>
Dionysia Petropoulou, 2025

---

# Table of contents
- Background & Objectives
- Definitions & Terminology
- Experimental Setup
- Taxonomy of Algorithms
- Deep Learning Methods
- Conclusions & Insights

---

# Motivation

- Revisits the 2017 “bake-off” comparing 18 TSC algorithms on 85 datasets.

- TSC field has expanded → 112 datasets, many new algorithms.

- Goal: evaluate progress and identify state-of-the-art methods.

---

# Background & Objectives

- Time Series Classification (TSC): predicting class labels from sequential data.

- 2017 bake-off: 5 categories (distance, interval, shapelet, dictionary, hybrid).

- This study adds 3 new categories: convolution-based, feature-based, and deep learning.

- Objectives:

  - Review and evaluate new TSC algorithms (2017–2023).

  - Compare to previous best-in-class.

  - Extend dataset benchmark with 30 new problems.

  ---

# Definitions & Terminology

  - Time Series (TS): ordered sequence of values $A = [a_1, \ldots, a_m]$
  - Multivariate TS (MTS): each observation $a_i \in \mathbb{R}^d$
  - Dataset: collection of time series
$$
D = \{(A^{(i)}, y^{(i)})\}
$$

-  Subseries: contiguous subsequence A_{i,l}.

- Sliding Window: generates all subseries of length l.
- Convolution: sliding dot product between a kernel and a time series.
- Dilation: spaced sampling for multi-scale analysis.

--

![Histogram](figures/sliding_window.png)

---

# Experimental Setup

- 112 datasets from UCR archive + 30 new datasets.

- 30 resamples per dataset for reproducibility.

- Metrics: Accuracy, Balanced Accuracy, AUROC, Negative Log Likelihood.

- Benchmark: 1-NN Dynamic Time Warping (DTW).

- Visual: schematic of critical difference plots or dataset table.

---

# Taxonomy of Algorithms

- Distance-based

- Feature-based

- Interval-based

- Shapelet-based

- Dictionary-based

- Convolution-based

- Deep learning-based

- Hybrid

---

# Deep Learning Approaches Tested

![Histogram](figures/DL_classifiers.png)

--

# Convolutional Neural Network

![Histogram](figures/fig3.png)

--

# Residual Network (ResNet)

![Histogram](figures/resnet.png)

--

# Inception Time

![Histogram](figures/inctime.png)

--

# H-InceptionTime (Hybrid inception)

H-InceptionTime = a hybrid version of the InceptionTime model.
- It combines the strengths of InceptionTime (multi-scale feature learning) and ResNet (residual connections that stabilize deep training).

# LITEtime (Light Inception with boosTing tEchniques).

- LITE: nearly the same accuracy, much faster and easier to train.
Great for real-time or low-resource applications.

# Conclusions & Insights

- **H-inception time** delivers the **highest accuracy** among tested models.  
- Combines:
  - InceptionTime’s **multi-scale pattern detection**, and  
  - ResNet’s **residual connections** for stable training.  
- Efficient thanks to **bottleneck layers**.  
- Outperforms both **ResNet** and **plain InceptionTime**.  
- **Best trade-off** between accuracy, stability, and computation cost.

---

Thank you!

















