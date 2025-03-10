### Mini Description

Methods that modify the training process to improve robustness, including adversarial training, robust optimization, and curriculum learning approaches.

### Description

Training-based defenses modify the learning process of AI systems to inherently develop robust features and decision boundaries that are less susceptible to adversarial perturbations. These approaches typically involve augmenting the training objective or data distribution to explicitly account for potential adversarial inputs. The most successful and widely-studied approach is adversarial training, which incorporates adversarial examples into the training process, though this comes with significant computational costs and potential trade-offs with standard accuracy.

Recent research has explored various modifications to the basic adversarial training framework, including alternative loss functions, dynamic adversary generation, and curriculum strategies that gradually increase attack strength during training. These approaches aim to address key challenges such as catastrophic forgetting of natural examples, sensitivity to the choice of attack parameters, and the difficulty of scaling to larger models and datasets. Researchers have also investigated methods for improving the sample efficiency of robust training and techniques for maintaining robustness across different types of perturbations.

Emerging directions focus on understanding the fundamental principles that enable successful robust training, including the role of data augmentation, the importance of feature learning, and the relationship between robustness and model capacity. There is increasing interest in methods that can provide theoretical guarantees about the robustness achieved through training, as well as approaches that can maintain robustness while scaling to larger models and more complex domains. Key open questions include how to reduce the computational burden of robust training and how to better balance the trade-off between standard and adversarial accuracy.

### Order

1. Adversarial_Training_Methods
2. Loss_Function_Design
3. Curriculum_Strategies
4. Data_Augmentation_Techniques
5. Efficiency_Optimization
