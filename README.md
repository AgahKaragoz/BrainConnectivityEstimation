# BrainConnectivityEstimation

Brain is very complex and complicated network. To estimate how it is going to act in the future is hard. Machine learning methods have to used. So, we use support vector regression and outlier reducing methods to predict how brain connectivities between different regions will change. With this information we can detect illnesses long before they showed up.


# Dataset
Given an elderly population, ach brain is encoded in a symmetric connectivity matrix 𝐗 ∈ R^35 ×R^35, where an element 𝐗(i, j)
denotes the strength of the connectivity between two brain regions i and j. By vectorizing the off-diagonal upper triangular
part of 𝐗, we generate a feature vector 𝐱 ∈ R^(1×d) (d = 595) representing a single sample (i.e., brain). By stacking the samples vectors vertically across N=150 subjects, we construct the data matrix 𝐃 ∈ R^(N×d).

By measuring the brain connectivity at two different timepoints t0 and t1, spaced out by 6 months, we can track the changes in the brain as a network. The goal of this project is to predict brain connectivity features at t1 from brain connectivity measured at a previous timepoint t0.
