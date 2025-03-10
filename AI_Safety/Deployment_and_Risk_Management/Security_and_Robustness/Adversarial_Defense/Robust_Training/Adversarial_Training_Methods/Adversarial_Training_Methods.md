### Mini Description

Techniques that directly incorporate adversarial examples into the training process, including PGD-based training, FGSM training, and their variants.

### Description

Adversarial training methods represent the core techniques for directly incorporating adversarial examples into model training to improve robustness. These methods typically involve generating adversarial examples during training and including them in the optimization objective, effectively teaching the model to resist potential attacks. The fundamental approach involves alternating between creating adversarial perturbations and updating model parameters to minimize loss on both clean and adversarial examples.

The field has evolved from simple single-step methods like Fast Gradient Sign Method (FGSM) training to more sophisticated iterative approaches such as Projected Gradient Descent (PGD) training. While PGD training is often considered the gold standard for empirical robustness, it comes with significant computational overhead. This has led to research into various approximations and optimizations that attempt to maintain robustness guarantees while reducing training time.

Current research challenges include developing methods that can scale to larger models and datasets, handling multiple threat models simultaneously, and addressing the trade-off between robustness and standard accuracy. There is particular interest in approaches that can provide theoretical guarantees about the resulting robustness, as well as techniques that can adapt to different perturbation types and magnitudes during training.

### Order

1. Single-Step_Methods
2. Iterative_Methods
3. Dynamic_Adversary_Generation
4. Multi-Task_Integration
5. Optimization_Techniques
