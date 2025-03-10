### Mini Description

Techniques that utilize model gradients to craft adversarial examples, including fast gradient sign method (FGSM), projected gradient descent (PGD), and their variants.

### Description

Gradient-based methods represent the foundational approach to generating adversarial examples, leveraging the differentiable nature of neural networks to directly optimize perturbations that maximize model error. These techniques compute the gradient of the loss function with respect to the input, identifying directions in input space that most effectively change the model's output. The computational efficiency and theoretical grounding of these methods have made them both practical tools for testing model robustness and valuable subjects for theoretical analysis.

The field has evolved from simple single-step methods like FGSM to more sophisticated iterative approaches such as PGD, which is often considered the 'standard' strong attack. Modern variants incorporate additional constraints and objectives, such as maintaining perceptual similarity, minimizing perturbation magnitude across different norms, or optimizing for specific target classes. Researchers have developed techniques to handle gradient masking, overcome local optima, and maintain effectiveness against various defensive mechanisms.

Current research challenges include developing methods that remain computationally feasible for large-scale models while maintaining attack strength, addressing the challenge of noisy or obfuscated gradients, and creating attacks that generalize better across different models and defense mechanisms. There's particular interest in techniques that can generate more natural or semantically meaningful adversarial examples while still leveraging gradient information effectively.

### Order

1. Single-Step_Methods
2. Iterative_Optimization
3. Constraint_Handling
4. Gradient_Enhancement
5. Multi-Objective_Optimization
