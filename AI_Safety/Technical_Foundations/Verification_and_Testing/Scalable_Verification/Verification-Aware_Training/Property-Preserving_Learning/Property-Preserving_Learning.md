### Mini Description

Techniques for ensuring that specific verifiable properties are maintained throughout the training process, including invariant learning and constraint satisfaction approaches.

### Description

Property-Preserving Learning focuses on developing training methodologies that maintain specific verifiable properties throughout the entire learning process, rather than attempting to enforce them after training. This approach treats desired properties - such as safety constraints, fairness criteria, or behavioral invariants - as fundamental aspects of the learning algorithm itself, ensuring they are preserved at each step of model updates rather than potentially violated and later corrected.

Current research explores various mathematical frameworks for expressing and enforcing invariants during training, including barrier functions, differential invariants, and constraint satisfaction programming adapted for neural networks. Key challenges include developing efficient methods to project gradient updates onto constraint-satisfying manifolds, handling competing or potentially contradictory properties, and maintaining property preservation when scaling to larger models and more complex properties.

A particular focus is on the development of provable guarantees that properties are truly preserved throughout training, rather than approximately or probabilistically maintained. This includes research on continuous-time training dynamics, formal methods for verifying training procedures themselves, and techniques for handling the interaction between property preservation and optimization objectives. The field also investigates how to handle properties that emerge from the composition of simpler invariants, and how to maintain properties in the presence of distribution shift or domain adaptation.

### Order

1. Invariant_Projection_Methods
2. Continuous-Time_Property_Evolution
3. Compositional_Property_Preservation
4. Property-Guided_Architecture_Design
5. Dynamic_Property_Adaptation
