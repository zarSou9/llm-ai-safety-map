### Mini Description

Techniques that use model gradients to determine feature importance, including integrated gradients, gradient-weighted class activation mapping, and saliency maps.

### Description

Gradient-based attribution methods leverage the model's gradients with respect to input features to determine their importance in specific predictions. These approaches are computationally efficient and directly connected to the model's learning process, making them particularly suitable for deep neural networks. The fundamental principle is that the gradient magnitude of the output with respect to an input feature indicates that feature's influence on the model's decision.

While basic saliency methods simply use raw gradients, more sophisticated approaches have been developed to address their limitations. These include techniques like integrated gradients, which accumulate gradients along a path from a baseline to the input, and SmoothGrad, which averages gradients over noisy versions of the input to produce more visually coherent attributions. Gradient-based methods must carefully handle issues like saturation (where gradients approach zero despite feature importance) and discontinuities in the gradient field.

Current research focuses on developing theoretically grounded approaches that satisfy desirable properties like completeness (attributions sum to the output difference) and implementation invariance (equivalent networks produce identical attributions). There is particular interest in methods that can handle non-differentiable operations, provide better computational efficiency for large models, and produce more human-interpretable attributions. Researchers are also exploring ways to combine gradient information with other forms of analysis to create more robust attribution methods.

### Order

1. Basic_Saliency_Methods
2. Path_Integration_Techniques
3. Gradient_Smoothing_Approaches
4. Backpropagation_Variants
5. Axiomatic_Methods
