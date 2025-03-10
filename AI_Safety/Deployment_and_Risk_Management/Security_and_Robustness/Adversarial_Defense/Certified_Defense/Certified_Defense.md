### Mini Description

Methods that provide mathematical guarantees about model behavior under bounded adversarial perturbations, including randomized smoothing and interval bound propagation.

### Description

Certified defense represents a rigorous approach to adversarial robustness that provides provable guarantees about model behavior under specific types of adversarial perturbations. Unlike empirical defenses that may be vulnerable to stronger attacks, certified defenses offer mathematical certainty about the maximum possible change in model output given bounded input perturbations. These methods typically trade some model accuracy or computational efficiency for guaranteed safety properties.

The field encompasses both deterministic and probabilistic certification approaches. Deterministic methods, such as complete verification and interval bound propagation, provide exact guarantees but often scale poorly with model size. Probabilistic approaches, like randomized smoothing, offer statistical guarantees that scale to larger networks but provide slightly weaker assurances. Recent work has focused on improving the scalability-precision trade-off and extending certification to more complex model architectures and threat models.

Current research challenges include developing tighter bounds for certification, reducing the computational overhead of verification procedures, and extending certification to new types of guarantees beyond traditional robustness properties. There is particular interest in certificates that can account for more realistic threat models, including semantic perturbations and real-world transformations, as well as methods that can certify properties about model behavior in deployment environments.

### Order

1. Complete_Verification
2. Relaxation_Methods
3. Probabilistic_Certification
4. Certification_Scaling
5. Property_Specification
