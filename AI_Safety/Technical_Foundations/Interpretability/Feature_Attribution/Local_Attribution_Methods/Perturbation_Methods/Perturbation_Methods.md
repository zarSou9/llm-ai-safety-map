### Mini Description

Approaches that measure feature importance by observing changes in model output when inputs are modified or removed, including LIME and SHAP.

### Description

Perturbation methods analyze model behavior by systematically modifying inputs and observing the resulting changes in output. These approaches are founded on the intuition that features important to a prediction will, when altered, cause significant changes in the model's output. Unlike gradient-based methods, perturbation approaches can be applied to any model regardless of architecture or differentiability, making them particularly valuable for black-box systems.

Current research focuses on developing efficient sampling strategies to reduce the computational cost of perturbations while maintaining explanation quality. Key challenges include selecting appropriate baseline distributions for feature removal, handling feature correlations, and determining optimal perturbation granularity. Researchers must also address the trade-off between local accuracy (how well the explanation fits the specific instance) and stability (how consistent explanations are across similar instances).

Emerging areas include developing model-agnostic approaches that can handle structured inputs like text or graphs, methods for explaining higher-level features or concepts rather than raw inputs, and techniques for generating counterfactual explanations through strategic perturbations. There is particular interest in approaches that can efficiently explain decisions from large language models, where traditional perturbation methods may be computationally prohibitive or semantically inappropriate.

### Order

1. Occlusion_Analysis
2. Surrogate_Modeling
3. Sampling_Strategies
4. Feature_Coalitions
5. Reference_Distribution
