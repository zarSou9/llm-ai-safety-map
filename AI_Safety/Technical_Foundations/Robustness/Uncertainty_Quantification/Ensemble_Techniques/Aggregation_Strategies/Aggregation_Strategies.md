### Mini Description

Techniques for combining predictions from ensemble members to produce final outputs and uncertainty estimates, including voting schemes, statistical aggregation, and learned combination methods.

### Description

Aggregation Strategies in ensemble techniques focus on methods for combining predictions and uncertainty estimates from multiple ensemble members into coherent final outputs. This involves both the mathematical frameworks for fusion of predictions and the development of techniques that preserve or enhance the uncertainty quantification properties of the ensemble. Key challenges include maintaining proper calibration after aggregation, handling correlations between ensemble members, and developing computationally efficient methods that scale to large ensembles.

Current research explores various approaches, from simple statistical aggregation methods like averaging and voting to more sophisticated techniques that learn optimal combination weights or adapt to input characteristics. Particular attention is paid to methods that can capture different types of uncertainty - combining epistemic uncertainty estimates from model disagreement with aleatoric uncertainty estimates from individual models. Recent work has also investigated aggregation strategies that are robust to outliers or adversarial ensemble members.

Emerging directions include the development of hierarchical aggregation methods for very large ensembles, techniques that preserve uncertainty structure across multiple prediction tasks, and approaches that can adaptively adjust aggregation strategies based on reliability metrics. There is also growing interest in methods that can provide theoretical guarantees about the properties of aggregated predictions and uncertainty estimates, particularly in safety-critical applications.

### Order

1. Statistical_Fusion
2. Learned_Aggregation
3. Hierarchical_Methods
4. Robust_Combination
5. Calibration-Aware_Fusion
