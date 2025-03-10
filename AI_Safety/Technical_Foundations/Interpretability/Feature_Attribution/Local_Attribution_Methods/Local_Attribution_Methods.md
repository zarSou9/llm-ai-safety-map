### Mini Description

Techniques for explaining individual predictions by attributing importance to specific input features or model components, including gradient-based methods and perturbation analyses.

### Description

Local attribution methods focus on explaining individual model predictions by assigning importance scores to specific input features or model components. These techniques aim to answer questions like 'Which parts of this input were most responsible for this particular output?' and 'How did different components of the model contribute to this specific decision?' The methods range from simple gradient-based approaches to sophisticated techniques that account for non-linear interactions and reference points.

Current research in local attribution has evolved from basic sensitivity analysis to more nuanced approaches that consider the model's decision boundary, feature interactions, and computational efficiency. Key challenges include ensuring attribution faithfulness (accurately reflecting the model's decision process), attribution stability (producing consistent results for similar inputs), and handling different types of input modalities and model architectures. Researchers must also balance the trade-off between computational complexity and attribution quality.

Emerging areas of focus include developing methods that can handle large-scale models efficiently, incorporating uncertainty quantification into attribution scores, and creating attribution techniques that are themselves interpretable to users. There is particular interest in methods that can attribute importance not just to raw input features but also to learned representations and intermediate computations within the model. The field is also exploring ways to validate attribution methods through both theoretical guarantees and empirical evaluation.

### Order

1. Gradient-Based_Methods
2. Perturbation_Methods
3. Counterfactual_Methods
4. Relevance_Propagation
5. Attention-Based_Attribution
