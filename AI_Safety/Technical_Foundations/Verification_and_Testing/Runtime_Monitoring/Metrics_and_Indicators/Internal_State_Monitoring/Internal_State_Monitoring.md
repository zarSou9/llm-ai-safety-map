### Mini Description

Indicators that track the internal computational patterns and representations within AI systems, including activation patterns, gradient flows, and attention mechanisms.

### Description

Internal State Monitoring focuses on tracking and analyzing the computational patterns, representations, and dynamics occurring within AI systems during operation. This involves developing methods to observe neural network activations, attention patterns, learned representations, and other internal mechanisms that govern system behavior. The challenge lies in identifying which internal signals are most relevant for safety monitoring while managing the vast amount of potential data that could be collected.

Current research emphasizes developing interpretable abstractions of internal states that can meaningfully characterize system behavior. This includes techniques for dimensionality reduction of activation spaces, methods for tracking the evolution of learned representations over time, and approaches for identifying critical neurons or circuits that may indicate safety-relevant behaviors. Researchers are particularly interested in developing monitoring approaches that can detect signs of emergent capabilities, deceptive behavior, or optimization pressure before they manifest in external behaviors.

A key area of investigation is the development of techniques that can maintain meaningful monitoring as systems become more complex. This includes work on identifying invariant properties of internal representations, developing hierarchical monitoring approaches that can track both low-level computations and high-level semantic features, and creating methods to detect when internal states begin to drift from their training distribution. The field also grapples with questions of how to validate that monitored internal states actually correspond to meaningful safety-relevant properties.

### Order

1. Activation_Analysis
2. Representation_Tracking
3. Circuit_Monitoring
4. Gradient_Dynamics
5. State_Space_Analysis
