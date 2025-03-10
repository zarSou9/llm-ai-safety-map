### Mini Description

Metrics that quantify a system's resistance to intentionally crafted perturbations and attacks, including measures of minimum adversarial distortion and attack success rates.

### Description

Adversarial robustness measures quantify an AI system's resilience against deliberately crafted inputs designed to cause incorrect or harmful behavior. These metrics assess both the minimum perturbation required to cause system failure and the success rate of various attack strategies. The field has evolved from simple L-p norm measurements to more sophisticated approaches that consider semantic meaningfulness, transferability of attacks, and real-world applicability.

A key challenge in developing these measures lies in balancing different types of robustness and understanding their relationships. For instance, robustness against small pixel perturbations might not translate to robustness against naturally occurring transformations. Researchers must also consider the computational feasibility of measuring robustness, as exact computation of minimal adversarial perturbations is often NP-hard, leading to the development of various approximation techniques and bounds.

Current research focuses on developing more comprehensive and realistic robustness measures that go beyond simple perturbation metrics. This includes measures that account for attack transferability across models, metrics that consider the semantic meaningfulness of adversarial examples, and approaches that quantify robustness across different threat models and attack capabilities. There is particular interest in measures that can predict real-world robustness and generalize across different types of adversarial attacks.

### Order

1. Perturbation_Magnitude_Metrics
2. Attack_Success_Rate_Metrics
3. Certification_Measures
4. Transferability_Metrics
5. Semantic_Robustness_Measures
