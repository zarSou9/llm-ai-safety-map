### Mini Description

Frameworks based on measuring changes in state space, entropy, or information content of the environment, including approaches using attainable states and reachability analysis.

### Description

Information-Theoretic Measures in AI impact assessment leverage concepts from information theory to quantify how AI systems affect their environment's state space and information content. These approaches typically focus on measuring changes in the distribution of possible states, reachability of different configurations, or alterations to the informational structure of the environment. Key metrics include entropy-based measures, mutual information between system actions and environmental states, and complexity measures that capture changes in the environment's organizational structure.

Current research emphasizes developing measures that can capture both immediate and potential future impacts through changes in the space of possibilities. This includes work on attainable states analysis, which examines how AI actions affect the set of future states that remain accessible, and empowerment measures that quantify changes in an agent's control over its environment. Researchers are particularly focused on measures that remain meaningful under uncertainty and can handle partial observability of environmental states.

Significant challenges include developing computationally tractable approximations for theoretical measures, handling high-dimensional state spaces, and ensuring measures remain well-defined under composition of multiple actions or systems. There is particular interest in measures that can capture meaningful impacts while being resistant to specification gaming and remaining interpretable to human overseers. This includes work on relative information measures that compare states to reference distributions and methods for identifying and measuring relevant symmetries and conservation laws.

### Order

1. State_Space_Dynamics
2. Entropy-Based_Metrics
3. Empowerment_Analysis
4. Reference_Distribution_Methods
5. Symmetry_and_Invariance
