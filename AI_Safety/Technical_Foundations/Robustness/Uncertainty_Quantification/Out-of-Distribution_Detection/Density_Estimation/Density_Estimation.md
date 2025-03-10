### Mini Description

Methods that explicitly model the probability distribution of training data to identify anomalous inputs, including parametric and non-parametric approaches.

### Description

Density Estimation in out-of-distribution detection focuses on learning probabilistic models that capture the underlying distribution of training data to identify anomalous inputs. These methods aim to assign high likelihood to in-distribution samples and low likelihood to OOD samples, providing a principled framework for detection based on probability theory. The approach encompasses both explicit density models that directly estimate probability densities and implicit models that learn surrogate measures of data likelihood.

A key challenge in density estimation for OOD detection is the curse of dimensionality, as modern AI systems often operate in high-dimensional spaces where traditional density estimation techniques become intractable. This has led to the development of various approximation techniques, including normalizing flows, autoregressive models, and energy-based approaches. Recent work has also revealed paradoxical behaviors where simple density models can assign higher likelihoods to OOD samples than in-distribution data, spurring research into more robust estimation techniques.

Current research directions include developing scalable architectures for high-dimensional density estimation, investigating the relationship between likelihood and semantic meaningfulness, and combining density estimation with other OOD detection approaches. There's particular interest in methods that can handle multimodal distributions, capture hierarchical dependencies, and provide interpretable likelihood scores that correlate with human intuitions about data typicality.

### Order

1. Explicit_Density_Models
2. Energy-Based_Models
3. Kernel_Density_Estimation
4. Score-Based_Models
5. Likelihood-Free_Methods
