### Mini Description

Techniques for generating adversarial examples and probing model vulnerabilities, including gradient-based attacks, optimization approaches, and black-box methods.

### Description

Attack methods in adversarial robustness research focus on developing techniques to generate examples that cause AI systems to fail or behave incorrectly. These methods serve dual purposes: exposing vulnerabilities in existing systems to guide defense development, and providing insight into the fundamental limitations and behaviors of machine learning models. The field has evolved from simple gradient-based perturbations to sophisticated approaches that can generate realistic, physically realizable attacks.

Current research spans a spectrum of adversarial capabilities and knowledge assumptions. White-box attacks assume complete access to model architecture and parameters, enabling precise optimization of perturbations. Black-box approaches operate with limited information, often only accessing model outputs, and must employ more sophisticated search or transfer-based strategies. Between these extremes, grey-box attacks work with partial model information or auxiliary knowledge about training data or defense mechanisms.

Emerging directions include the development of attacks that are robust to defensive techniques, methods that generate semantically meaningful adversarial examples, and approaches that can efficiently scale to large models and high-dimensional input spaces. Researchers are particularly interested in attacks that can maintain effectiveness across model ensembles or transfer well between different architectures, as these often reveal more fundamental vulnerabilities in machine learning systems.

### Order

1. Gradient-Based_Methods
2. Score-Based_Methods
3. Decision-Based_Methods
4. Transfer-Based_Methods
5. Search-Based_Methods
